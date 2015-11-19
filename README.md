# phonegap-recordAndPlay
record and play audio in phonegap apps

Version: 0.0.1

Author: Christian Marienfeld post@chrisland.de


### Examples:

	var rap = new recordAndPlay();
	var success = function () { console.log('done'); };
	var error = function (err) { console.log(err); };
	rap.record(success, error);
	rap.play(success, error);

### Methods:

* **record(success, error)**  Open audio-record OS App
* **play(success, error)**  Play recorded file


### Params:

  *nothing*

### Return:

* **Object** recordAndPlay Object
