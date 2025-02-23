# React
React is a javaScript library for building user interfaces.
* Declarative : React makes it painless to creat interactive UIs.Design simple views for each state in your application ,and React will efficidently update and render just the right components when you data changes.Declartive views make your code more predictable ,simple to understand,and easier to debug.
* Component-Based:Build encapsulated components that manage their own state ,then compose them to make complex ULs.Since component logic is written is JavaScript instead of templates,you can easier pass rich data through your app and keep the state out of the DOM.
* Learn Once,Write Anywhere:We don't make assumptions about the rest of your technology stack,so you can develop new features in React without rewriting existing codes.React can also render on the server using <u>Node</u>  and  power mobile apps using <u>React Native</u>.

<u>Learn how to use React in your project</u>

## Installation
React has been designed for gradual adoption from the start,and **you can use as little or as much React as you need** :
* use <u>Quick Start</u> to get a taste of React.
* <u>Add React to Existing Project</u> to use as little or as much React as you need .
* <u>Creat a New React APP</u> if you're looking for a powerful JavaScript toolchain.

## Documentation
You can find the React documentation <u>on the website</u>.

Check out the <u>Getting Started</u> page for a quick overview.

The documentation is divided into several sections:
* <u>Quick Start</u>
* <u>Tutorial</u>
* <u>Think in React</u>
* <u>installation</u>
* <u>Describing the UI</u>
* <u>Adding interactivity</u>
* <u>Managing State</u>
* <u>Advanced Guides</u>
* <u>API Reference</u>
* <u>Where to Get Support</u>
* <u>Contributing Guide</u>

You can improve it by sending pull requests to <u>this repository</u>.
## Examples
We have several examples <u>on the website</u>.Here is the first one to get you started:
```
import  { createRoot } from 'react-dom/client';
 
 function HelloMessage({ name }) {
    return <div>hello {name}<div>;
 }

 const root = createRoot(document.getElementById('container'));
 root.render(<HelloMessage name="Taylor"/>);
```
This examples will render "Hello Tylor" into a container on the page.

You'll notice that we used an HTML -like syntax;<u>we call it JSX</u>.JSX is not required to use React ,but is makes code more readable,and writing it feels like writing HTML.
## Contributing
The main purpose of this repository is to continue evolving React core,making it faster an easier to use.
Development of React happens in the open on Github, and we grateful to the community for contributing bugfixes and improvements.Read below to learn how you can take part in improving React.
### Code of Conduct
Facebook has adoped a Code of Conduct that we expect project participants to adhere to. Please read <u>the full text</u> so that you can understand what actions will and will not be tolerated.
### Contributing Guide
Read our<u>contributing guide</u> to learn about our development process, how to propose bugfixes and improvements,and how to build and test your changes to React.
### Good First Issues
To help you get your feet wet and get you familiar with our contribution process,we have a list of <u>good first issues</u> that contain bugs that have a relatively limited scope.This is a great place to get started.

### License
React is <u>MIT licensed</u>.