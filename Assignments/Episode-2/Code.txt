import React from "react";
import ReactDOM from 'react-dom/client'

const heading = React.createElement("div", { id: "parent" },
    [React.createElement("div", { id: "child" },
        [React.createElement("h1", { id: "" }, "Im H1 Tag"),
        React.createElement("h2", { id: "" }, "Im H2 Tag")]
    ),
    React.createElement("div", { id: "child" },
        [React.createElement("h1", { id: "" }, "Im H1 Tag"),
        React.createElement("h2", { id: "" }, "Im H2 Tag")]
    )
    ]
);



const root = ReactDOM.createRoot(document.getElementById("root"));

root.render(heading)