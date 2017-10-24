# asynEach
Asynchronous each. Control delay and step.
Example <br>
[1,2].asyncEach(100,function(d){ <br>
	console.log(d) <br>
	},function(item,resume){ <br>
		console.log(item); <br>
		resume(); <br>
	}); <br>
Jquery Usage<br>
$('p').toArray().asyncEach(100,function(d){ <br>
	console.log(d) <br>
	},function(item,resume){ <br>
		console.log(item); <br>
		resume(); <br>
	}); <br>
  resume controls stepper
