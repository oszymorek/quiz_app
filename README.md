<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6295/6295417.png" width="100" />
</p>
<p align="center">
    <h1 align="center">QUZI_APP</h1>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/oszymorek/quzi_app.git?style=flat&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/oszymorek/quzi_app.git?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/oszymorek/quzi_app.git?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/oszymorek/quzi_app.git?style=flat&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&logo=JavaScript&logoColor=black" alt="JavaScript">
	<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=flat&logo=HTML5&logoColor=white" alt="HTML5">
	<img src="https://img.shields.io/badge/React-61DAFB.svg?style=flat&logo=React&logoColor=black" alt="React">
	<img src="https://img.shields.io/badge/Axios-5A29E4.svg?style=flat&logo=Axios&logoColor=white" alt="Axios">
	<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON">
</p>
<hr>


## Project #7 - Quiz Application

A simple App to quiz you on your React knowledge. 

<strong>Creation Process</strong> </br>
<strong>Initialising the project:</strong> I used create-react-app to create the basic structure of the project.</br>
<strong>Component creation:</strong> Each section of the page was implemented as a separate React component.</br>
<strong>Props:</strong> Used `{children}` to pass components into component.</br>
<strong>Data:</strong> Data is passed in via props(props drilling).</br>
<strong>Styling:</strong> Application of CSS styles to give the page an aesthetically pleasing look.</br>
<strong>Hooks:</strong> Used the `useReducer` | `useEffect` hooks.</br>
<strong>Functions:</strong> `Data fetch` | `Correctly answer` | `Next question` | `Finish quiz` | `Reset quiz` | `Time` |  `Counter` |</br>
<strong>Deployment:</strong> The project was deployed on Netlify so that it could be available to the public.</br>

https://project07-oszymorek.netlify.app/

```sh
└── quzi_app/
    ├── README.md
    ├── data
    │   └── questions.json
    ├── package-lock.json
    ├── package.json
    ├── public
    │   ├── index.html
    │   ├── logo192.png
    │   └── logo512.png
    └── src
        ├── App.js
        ├── components
        │   ├── DataCounter.js
        │   ├── Error.js
        │   ├── Finished.js
        │   ├── Footer.js
        │   ├── Header.js
        │   ├── Loader.js
        │   ├── Main.js
        │   ├── NextButton.js
        │   ├── Option.js
        │   ├── Progress.js
        │   ├── Question.js
        │   ├── StartScreen.js
        │   └── Timer.js
        ├── index.css
        └── index.js
```
