<!-- Contacts.svelte -->
<script>
    export let contacts = [
      { name: 'Bakytbek Eshmurzaev', email: 'eshmurzaev_b@auca.kg', phone: '555-1234', address: 'Исы Ахунбаева, 133' },
      { name: '-', email: '-', phone: '-', address: '-' }
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
            <a href={`https://go.2gis.com/4mqjp`} class="address-link" target="_blank" rel="noopener noreferrer">
              {contact.address}
            </a>
          </p>
      </div>
    {/each}
  </div>
  