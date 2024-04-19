:root {
--card-height: 300px;
--card-width: calc(var(--card-height) / 1.5);
}
{
box-sizing: border-box;
}
body {
width: 100vm;
height: 100vh;
margin: 0;
display: flex;
justify-content: center;
align-items: center;
background: #47289d;
}
.card {
width: var(--card-width);
height: var(--card-height);
position: relative;
display: flex;
justify-content: center;
align-items: flex-end;
padding: 0 36px;
perspective: 2500px;
margin: 0 50px;
}
