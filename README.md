<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NGO Awareness Initiative</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f5f7fa;
    color:#333;
    line-height:1.6;
}

header{
    background:linear-gradient(135deg,#2e7d32,#4caf50);
    color:white;
    text-align:center;
    padding:80px 20px;
}

header h1{
    font-size:48px;
}

header p{
    font-size:20px;
    margin-top:10px;
}

.hero{
    background:url('https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?auto=format&fit=crop&w=1200&q=80');
    background-size:cover;
    background-position:center;
    text-align:center;
    color:white;
    padding:120px 20px;
}

.hero h2{
    font-size:42px;
    margin-bottom:10px;
}

.container{
    width:90%;
    max-width:1100px;
    margin:auto;
}

section{
    padding:50px 0;
}

.card{
    background:white;
    padding:25px;
    border-radius:12px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

h2{
    color:#2e7d32;
    margin-bottom:15px;
}

.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.project{
    background:white;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
    transition:0.3s;
}

.project:hover{
    transform:translateY(-8px);
}

.project img{
    width:100%;
    height:180px;
    object-fit:cover;
}

.project-content{
    padding:15px;
}

.stats{
    display:flex;
    justify-content:space-around;
    text-align:center;
    flex-wrap:wrap;
}

.stats h3{
    font-size:36px;
    color:#2e7d32;
}

.cta{
    text-align:center;
    background:#2e7d32;
    color:white;
    padding:50px 20px;
    border-radius:12px;
}

.cta button{
    margin-top:15px;
    padding:14px 30px;
    border:none;
    border-radius:30px;
    background:white;
    color:#2e7d32;
    font-weight:bold;
    cursor:pointer;
}

footer{
    text-align:center;
    background:#222;
    color:white;
    padding:20px;
}
</style>
</head>

<body>

<header>
    <h1>NGO Awareness Initiative</h1>
    <p>Creating Positive Impact Through Community Service</p>
</header>

<section class="hero">
    <h2>Together We Can Make A Difference</h2>
    <p>Supporting Education, Environment & Community Welfare</p>
</section>

<div class="container">

<section>
    <div class="card">
        <h2>About Our NGO</h2>
        <p>
            Our NGO is committed to creating meaningful social impact through
            education, environmental sustainability, community development,
            and youth empowerment initiatives.
        </p>
    </div>
</section>

<section>
    <h2>Ongoing Projects</h2>

    <div class="projects">

        <div class="project">
            <img src="https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&w=600&q=80">
            <div class="project-content">
                <h3>Education Support</h3>
                <p>Providing learning resources and mentorship programs.</p>
            </div>
        </div>

        <div class="project">
            <img src="https://images.unsplash.com/photo-1542601906990-b4d3fb778b09?auto=format&fit=crop&w=600&q=80">
            <div class="project-content">
                <h3>Green Environment</h3>
                <p>Tree plantation and environmental awareness campaigns.</p>
            </div>
        </div>

        <div class="project">
            <img src="https://images.unsplash.com/photo-1469571486292-b53601010376?auto=format&fit=crop&w=600&q=80">
            <div class="project-content">
                <h3>Community Development</h3>
                <p>Supporting communities through welfare programs.</p>
            </div>
        </div>

    </div>
</section>

<section>
    <div class="card">
        <h2>Our Impact</h2>

        <div class="stats">
            <div>
                <h3>1000+</h3>
                <p>Students Supported</p>
            </div>

            <div>
                <h3>500+</h3>
                <p>Volunteers</p>
            </div>

            <div>
                <h3>50+</h3>
                <p>Projects Completed</p>
            </div>
        </div>
    </div>
</section>

<section>
    <div class="cta">
        <h2>Join Us Today</h2>
        <p>Become a volunteer and help create positive change.</p>
        <button>Volunteer Now</button>
    </div>
</section>

</div>

<footer>
    <p>© 2026 NGO Awareness Initiative | Internship Project</p>
</footer>

</body>
</html>