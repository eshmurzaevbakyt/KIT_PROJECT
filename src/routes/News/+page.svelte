<script>
    // Import the Link component from $app/navigation
    import { Link } from '$app/navigation';
  </script>
  
  <style>
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        margin: 0;
        padding: 0;
        background: #f4f4f4;
    }
    
    header {
        background: #333;
        color: #fff;
        padding: 10px 0;
        text-align: center;
    }
    
    nav ul {
        padding: 0;
        list-style: none;
    }
    
    nav ul li {
        display: inline;
        margin-right: 10px;
    }
    
    nav ul li a {
        color: #fff;
        text-decoration: none;
    }
    
    section#news-articles {
        width: 80%;
        margin: 20px auto;
        padding: 20px;
        background: white;
    }
    
    article {
        margin-bottom: 20px;
        padding-bottom: 10px;
        border-bottom: 1px solid #eaeaea;
    }
    
    h2 {
        color: #333;
    }
    
    p {
        margin: 0 0 10px;
    }
    
    </style>
  
  <header>
    <h1>Latest News</h1>
    <nav>
      <ul>
        <li><Link href="https://kit-project.vercel.app/">Home</Link></li>
      </ul>
    </nav>
  </header>
  
  <section id="news-articles">
    <article>
      <h2>News Article Title 1</h2>
      <p>This is a summary of the first news article. It could be a few sentences long.</p>
    </article>
    <article>
      <h2>News Article Title 2</h2>
      <p>This is a summary of the second news article. More details and information here.</p>
    </article>
    <!-- Add more articles here -->
  </section>
  

