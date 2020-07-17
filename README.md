# react-internet-status
-A small react Component that indicates lost internet connectivity

### Installation
`npm install react-internet-status`

### Usage
`import { InternetStatus } from 'react-internet-status'`

```
function App(){
  return (
    <div>
      <InternetStatus />
    </div>
  );
}

export default App
```
- Render InternetStatus component in any parent component preferably in the App.js Component.

## Props

### PropTypes
<ul>
<li> message: PropTypes.string </li>
<li> bgColor: PropTypes.string </li>
<li> txColor: PropTypes.string </li>
<li> wd: PropTypes.string </li>
<li> ht: PropTypes.string </li>
</ul>

### DefaultProps
<ul>
<li> message: 'Your device is not connected to the internet!' </li>
<li> bgColor: 'red' </li>
<li> txColor: 'white' </li>
<li> wd: '100%' </li>
<li> ht: '50px' </li>
</ul>

## Author
- Martins Obayomi
