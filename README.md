# react
hello_world
#the main focus of any react app is on the scr folder

#index.js
import React from 'react';
import ReactDOM from 'react-dom';
import App from './App';

ReactDOM.render(<App />,document.getElementById('root'));

#App.js
import React from 'react';

const App=()=>{
	return(
		<h1> HELLO WORLD!! </h1>
		);
}

export default App;



