import React from "react";
import ReactDOM from 'react-dom/client'

const Header = () => {
    return (
        <nav id="main-nav" className="tranformClass">
            <div className="left-menu">
                <div className="nav-logo">
                    <a href=""> <img src="https://static.wixstatic.com/media/84b06e_717d310324e54451a0195d5658c70004~mv2.png/v1/fill/w_640,h_366,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/84b06e_717d310324e54451a0195d5658c70004~mv2.png" alt="logo" /></a>
                </div>
            </div>
            <div className="mid-menu">
                <input type="text" placeholder="Search..." />
            </div>
            <div className="right-menu">
                <img src="https://png.pngtree.com/element_our/20200610/ourmid/pngtree-character-default-avatar-image_2237203.jpg" />
            </div>
        </nav>
    )
}



const root = ReactDOM.createRoot(document.getElementById("root"));

root.render(<Header />)