<!-- Contacts.svelte -->
<script>
    export let contacts = [
      { name: 'Bakytbek Eshmurzaev', email: 'eshmurzaev_b@auca.kg', phone: '555-1234', address: 'https://go.2gis.com/4mqjp' },
      { name: 'Jane Doe', email: 'jane@example.com', phone: '555-5678', address: '456 Oak St, Town' }
    ];
  </script>
  
  <style>
    /* Add your styling for the Contacts page here */
    .contacts-container {
      padding: 20px;
      text-align: center;
    }
  
    .contact-card {
      border: 1px solid #ccc;
      padding: 10px;
      margin-bottom: 15px;
      text-align: left;
    }
  </style>
  
  <div class="contacts-container">
    <h1>Contact Information</h1>
    
    {#each contacts as contact (contact.name)}
      <div class="contact-card">
        <h2>{contact.name}</h2>
        <p>Email: {contact.email}</p>
        <p>Phone: {contact.phone}</p>
        <p>
            Address: 
            <a href={`https://go.2gis.com/4mqjp=${encodeURIComponent(contact.address)}`} class="address-link" target="_blank" rel="noopener noreferrer">
              {contact.address}
            </a>
          </p>
      </div>
    {/each}
  </div>
  