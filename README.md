# react
# creating element
const heading=React.createElement("div",{id:"parent"},[
    React.createElement("div",{id:"child1"},[
        React.createElement("h1",{},"hellooh1"),
        React.createElement("h2",{},"hellooh2")
    ]),
    React.createElement("div",{id:"child1"},[
        React.createElement("h1",{},"hellooh1"),React.createElement("h2",{},"hellooh2")
    ]),

]);
const root=ReactDOM.createRoot(document.getElementById("root"));
root.render(heading);
