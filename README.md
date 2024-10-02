<h1 align="center" id="title">Insight</h1>

<p id="description">A Movie Rated Website having a collection of movies across the world. Through this website you will able to get Movies / Webseries various information like year of release,director,cast,plot and rating given at different genuine website.</p>

<h2>🚀 Check it OUT 👇🏻</h2>

[https://harshit1142.github.io/Insight/](https://harshit1142.github.io/Insight/)

<h2>Project Screenshots:</h2>

<img src="/screenshot/SR1.png" alt="project-screenshot" width="200" height="200/">
<img src="/screenshot/SR2.png" alt="project-screenshot" width="200" height="200/">
<img src="/screenshot/sr3.png" alt="project-screenshot" width="200" height="200/">
<img src="/screenshot/SR4.png" alt="project-screenshot" width="200" height="200/">

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Collection of Top Rated,Top Grossing,Top Animated Movies.
*   A Movie/Webseries Searching Bar.
*   Responsive Website.
*   Contains movies and webseries informations / details..
*   A Collections of rating provided at different Genuine Website (Like : Internet Movie Database,Rotten Tomatoes,Metacritic )..

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   HTML
*   CSS
*   JAVASCRIPT
*   BOOTSTRAP
*   Use of an API(Application programming interface)

## Installation

To get started with the project, follow these steps:

1. **Clone the repository:**
   First, clone the repository to your local machine using the following command:
   ```bash
   git clone https://github.com/harshit1142/Insight.git
   ```

2. **Navigate to the project directory:**
   Change your current directory to the project directory:
   ```bash
   cd Insight
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributors 

<div align="center">
  <h3>Meet our amazing contributors</h3>
  <div id="contributors"></div>
</div>

<script>
  const repo = 'harshit1142/Insight';
  const contributorsUrl = `https://api.github.com/repos/${repo}/contributors`;

  fetch(contributorsUrl)
    .then(response => response.json())
    .then(contributors => {
      const contributorsDiv = document.getElementById('contributors');
      contributors.forEach(contributor => {
        const img = document.createElement('img');
        img.src = contributor.avatar_url;
        img.alt = contributor.login;
        img.width = 50;
        img.height = 50;
        img.style.borderRadius = '50%';
        img.style.margin = '5px';
        img.title = contributor.login;
        contributorsDiv.appendChild(img);
      });
    })
    .catch(error => console.error('Error fetching contributors:', error));
</script>


