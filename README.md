# technical-documentation-project
@ -1,10 +1,93 @@
html{
/* General */

html, body {
  font-family: 'Roboto', sans-serif;
  height: 100%;
  margin: 0;
}
\

/* code */

code {
  background-color: #f5f5f5;
  display: block;
  width: 100%;
  margin: 0 auto;
  font-size: 20px;
}

/* Headers */ 

.main-section header {
  font-size: 24px;
}

header {
  font-weight: bolder;
}

#navbar h1 {
  color: white;
  text-align: center;
  text-transform: uppercase;
}

.main-section header{
  color: #36B1BF;
  text-align: center;
}

/* Navbar */

nav ul {
  list-style: none;
  font-size: 20px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  border-bottom: 2px solid white;
}

/* Positioning */

#navbar {
  width: 20%;
  height: 100%;
  position: fixed;
  border-right: 5px solid #36B1BF;
  background-color: #F2385A;
}

/* Main area */

#main-doc {
  width: 80%;
  height: auto;
  position: absolute;
  right: 0;
}

.main-section {
  width: 90%;
  display: block;
  white-space: pre-wrap;
  margin: 0 auto;
  padding-bottom: 20px;
}

/* Media query */

@media (max-width: 500px) {
  h1 {
    font-size: 18px;
  }
}

/* Other */

hr {
  color: #36B1BF;
  border-top: 3px solid #36B1BF;
  margin-top: -10px;
} 
