MixItUp Debug Extension
=========

A debugging extension for MixItUp.

## General Use

This extension provides real time feedback about MixItUp's operations for use in debugging via the console.

To use, include the file in your project after the MixItUp core.

For each instance of MixItUp that you wish to debug, enable debugging via the configuration object as follows when instantiating:

```
$('#Container').mixItUp({
	debug: {
		enable: true
	}
});
```
> Enable debugging via the configuration object on instantiation.

## Debug Modes

A second configuration option `debug.mode` is provided to set the debug mode. The debug mode is set to `'normal'` by default. The modes `'quiet'` and `'verbose'` are also available:

```
$('#Container').mixItUp({
	debug: {
		enable: true,
		mode: 'verbose'
	}
});
```
> Enable verbose debugging.

### Quiet Mode

Show warnings only plus a single message on successful initialisation.

### Normal Mode

Show warnings and operational logs.

### Verbose Mode

Show everything.

<br/>
<hr/>

*&copy; 2014 KunkaLabs Limited.*
