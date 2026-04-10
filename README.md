*{
  margin:0px;
  padding:0px;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
.img1 img{
  width:3rem;
  height:3rem;
  
}
.img1 {
  margin: 0px;
  display: flex;
  flex-direction: column;
  align-items: center;
  font-weight: bold;
}
.img1 h2{
  font-weight:bold;
}
nav{
  padding:10px;
  display:flex;
  align-items:center;
  justify-content:space-between;
}
nav a{
  text-decoration:none;
  font-size:15px;
  font-weight:bold;
  color:black;
}

/* HERO */
.hero {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 50px;
  background-image:url(images/hero1.avif);
  background-repeat:no-repeat;
  background-size:cover;
}

.hero h1 {
  font-size: 50px;
}

.hero p {
  margin: 20px 0;
}

.btn {
  padding: 10px 20px;
  background: white;
  color: #4f46e5;
  text-decoration: none;
  border-radius: 5px;
  margin-right: 10px;
}
/* SERVICES */
.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  padding:25px;
}
.card {
  box-shadow:10px 10px 10px rgb(103, 95, 95);
  gap:10px;
  display:flex;
  flex-direction: column;
  align-items: center;
  background: white;
  padding: 20px;
  border-radius: 10px;
}
.portfolio {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}
.portfolio div {
  background:;
  height: 150px;
  border-radius: 10px;
}
.card img{
  height:9rem;
  width: 15rem;
}
.card p{
  font-weight:bold;
}
footer {
  background: #111;
  color: white;
  padding: 20px;
  text-align: center;
}
.cont{
  padding:10px;
  width:100vw;
  display:flex;
  flex-direction: column;
  align-items:center;
  /* background:linear-gradient(90deg, #fcff9e 0%, #c67700 100%); */
  background:rgb(195, 180, 180);
  position: relative;
}
.cont2{
  width:100vw;
  display:flex;
  padding:10px;
  position: relative;
  justify-content:center;
  gap:250px;

}
.form{
  display:flex;
  flex-direction: column;
  align-items:center;
}
form {
  max-width: 400px;
  margin: auto;
  display: flex;
  flex-direction: column;
}
input, textarea {
  margin: 10px 0;
  padding: 10px;
  border-radius:100px;
  box-shadow:5px 5px 4px;
}

button {
  padding: 10px;
  background: #4f46e5;
  color: white;
  border: none;
}
.address{
  display:flex;
  flex-direction: column;
  align-items:center;
  gap:50px

}
.mat{
  display:flex;
  flex-direction:column;
  gap:5px;
  align-items:center;
}
/* Responsive adjustments */
@media (max-width: 768px) {
    .hero {
        flex-direction: column;
        height: auto;
        text-align: center;
        padding: 30px;
    }

    .hero h1 {
        font-size: 36px;
    }

    .hero p {
        font-size: 18px;
    }

    .nav a {
        font-size: 14px;
    }

    .services {
        grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
        padding: 15px;
    }

    .card {
        width: 90%;
    }

    .portfolio {
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    }

    .portfolio div {
        height: auto;
    }

    .cont2 {
        flex-direction: column;
        gap: 50px;
    }

    .address, .form {
        width: 100%;
        gap: 20px;
    }

    .form input, .form textarea {
        padding: 8px;
    }
}
nav div {
    display: flex;
    gap:10px;
}

@media (max-width: 768px) {
    nav div {
        flex-direction: column;
        gap: 15px;
        align-items: center;
    }
}
.hero {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 50px;
    background-image: url(images/hero1.avif);
    background-repeat: no-repeat;
    background-size: cover;
    text-align: center;
}

.hero h1 {
    font-size: 50px;
}

.hero p {
    margin: 20px 0;
}

@media (max-width: 768px) {
    .hero h1 {
        font-size: 32px;
    }

    .hero p {
        font-size: 16px;
    }

    .btn {
        padding: 10px 15px;
    }
}
.services {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    padding: 25px;
}

@media (max-width: 768px) {
    .services {
        grid-template-columns: 1fr; /* single column on mobile */
        gap: 15px;
    }
}
.portfolio {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

@media (max-width: 768px) {
    .portfolio {
        grid-template-rows: 1fr; /* single column for mobile */
    }

    .portfolio div {
        height: auto;
    }
}
.portfolio {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    justify-items: center; /* Center items horizontally */
    padding: 40px;
}

.portfolio div {
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 90%;
    max-width: 300px; /* Limit width for each item */
    text-align: center;
}

.portfolio img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

.portfolio p {
    margin-top: 15px;
    font-weight: bold;
    font-size: 18px;
}

.portfolio div p:last-child {
    font-size: 14px;
    color: #555;
}

@media (max-width: 768px) {
    .portfolio {
        grid-template-columns: 1fr; /* single column on mobile */
        gap: 20px;
        padding: 20px;
    }

    .portfolio div {
        width: 100%; /* Ensure each div takes full width */
    }
}