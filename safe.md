@import url("https://fonts.googleapis.com/css2?family=Figtree:wght@400;600&display=swap");

body {
font-family: "Figtree", sans-serif;
}
:root {
--YELLOW: hsl(47, 88%, 63%);

--WHITE: hsl(0, 0%, 100%);

--GRAY500: hsl(0, 0%, 42%);
--Gray950: hsl(0, 0%, 7%);
--Weights: 800;
}

.container {
background-color: var(--WHITE);

width: 100vw;
height: 100vh;
display: flex;
align-items: center;
}
.container-box {
background-color: var(--YELLOW);
width: 90vw;
height: 90vh;
margin: 50px;
display: flex;
justify-content: center;
align-items: center;
}
.card {
background-color: var(--WHITE);
width: 280px;
height: 390px;
border-radius: 20px;
box-shadow: 5px 5px black;
}
.card-img1 {
width: 250px;
height: 200px;
border-radius: 40px;
margin-top: -20px;
}
.content {
padding: 15px;
font-weight: var(--Weights);
}
.box-learning {
width: 70px;
height: 20px;
border-radius: 2px;
display: flex;
align-items: center;
justify-content: center;
margin-top: -20px;
background-color: var(--YELLOW);
}
.sub-head {
color: var(--Gray950);
font-size: 12px;
font-weight: var(--Weights);
}
.parah {
font-size: 12px;
color: var(--GRAY500);
}
.user-content {
display: flex;
align-items: center;
margin-top: -10px;
}
.user-name {
margin-left: 10px;
}
