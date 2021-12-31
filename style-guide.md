# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Dark Violet: hsl(256, 26%, 20%)
- Grayish Blue: hsl(216, 30%, 68%)

### Neutral

- Very Dark Violet: hsl(270, 9%, 17%)
- Dark Grayish Violet: hsl(273, 4%, 51%)
- Very Light Gray: hsl(0, 0%, 98%)

## Typography

### Body Copy

- Font size: 16px

### Headings

- Family: [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display)
- Weights: 400

### Body

- Family: [Karla](https://fonts.google.com/specimen/Karla)
- Weights: 400, 700

## Icons

You can use either use the social icons provided or load in a font icon library. Some library suggestions can be found below:

- [Font Awesome](https://fontawesome.com)
- [IcoMoon](https://icomoon.io)
- [Ionicons](https://ionicons.com)

How we work
    Blog
    Account
    View plans
<div class="dropdown">
  <button onclick="myFunction()" class="dropbtn">Dropdown</button>
  <div id="myDropdown" class="dropdown-content">
    <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
  </div>
</div>

/* Dropdown Button */
.dropbtn {
  background-color: #3498DB;
  color: white;
  padding: 16px;
  font-size: 16px;
  border: none;
  cursor: pointer;
}

/* Dropdown button on hover & focus */
.dropbtn:hover, .dropbtn:focus {
  background-color: #2980B9;
}

/* The container <div> - needed to position the dropdown content */
.dropdown {
  position: relative;
  display: inline-block;
}

/* Dropdown Content (Hidden by Default) */
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

/* Links inside the dropdown */
.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

/* Change color of dropdown links on hover */
.dropdown-content a:hover {background-color: #ddd}

/* Show the dropdown menu (use JS to add this class to the .dropdown-content container when the user clicks on the dropdown button) */
.show {display:block;}


/* When the user clicks on the button,
toggle between hiding and showing the dropdown content */
function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown menu if the user clicks outside of it
window.onclick = function(event) {
  if (!event.target.matches('.dropbtn')) {
    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}


<span>
      <div class="dropdown">
        <button onclick="myFunction()" class="dropbtn"><img src="images/icon-hamburger.svg"></button>
        <div id="myDropdown" class="dropdown-content">
          <div>HOW WE WORK</div>
          <div>BLOG</div>
          <div>ACCOUNT</div>
          <div><button>VIEW PLANS</button></div>
        </div>
      </div>
    </span> 

    <span>
      <div class="nav">
          <div>HOW WE WORK</div>
          <div>BLOG</div>
          <div>ACCOUNT</div>
          <div><button>VIEW PLANS</button></div>
        </div>
      </div>
    </span> 