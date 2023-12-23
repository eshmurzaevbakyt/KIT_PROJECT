<script>
    import { Link } from '$app/navigation';
    
    // Placeholder data - in a real app, this might come from a CMS or API
    let vitamins = [
      { id: 1, name: 'Vitamin A', benefits: 'Supports vision, immune system, and reproduction.' },
      { id: 2, name: 'Vitamin B', benefits: 'Aids in energy production and cell metabolism.' },
      { id: 3, name: 'Vitamin C', benefits: 'Important for skin, bone, and blood vessel health.' },
      // ...add more vitamins as needed
    ];
  </script>
  
  <style>
    /* Add your styles here */
    header {
      background-color: #f4f4f4;
      padding: 1rem;
      text-align: center;
    }
  
    .vitamin-list {
      list-style: none;
      padding: 0;
    }
  
    .vitamin-item {
      background-color: white;
      margin: 1rem;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
  
    .vitamin-name {
      font-weight: bold;
    }
  </style>
  
  <header>
    <h1>Our Vitamins</h1>
    <nav>
      <ul>
        <li><Link href="/">Home</Link></li>
        <li><Link href="/news">News</Link></li>
        <!-- Add any other links here -->
      </ul>
    </nav>
  </header>
  
  <main>
    <ul class="vitamin-list">
      {#each vitamins as vitamin}
        <li class="vitamin-item">
          <div class="vitamin-name">{vitamin.name}</div>
          <div class="vitamin-benefits">{vitamin.benefits}</div>
        </li>
      {/each}
    </ul>
  </main>
  