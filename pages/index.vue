<!-- <template>
    <div>
      <div>Halo</div>
      <button id="open-app-button">
        <a id="deep-link" href="penabur://forgot_password/jbf-cajxkd-91b7d52ceb61b90f97db">
          <div>Go To App</div>
        </a>
      </button>
      <div v-if="fallbackVisible" id="fallback-message">
        The app did not open. <a :href="fallbackUrl">Click here</a> to continue.
      </div>
    </div>
  </template>
  
  <script lang="ts" setup>
  import { ref, onMounted } from 'vue';
  
  const fallbackVisible = ref(false);
  const fallbackUrl = 'https://example.com'; // Replace with your fallback URL
  
  onMounted(() => {
    const deepLinkElement = document.getElementById('deep-link') as HTMLAnchorElement;
  
    if (deepLinkElement) {
      // Attempt to open the app via the deep link
      deepLinkElement.click();
  
      // Set a timeout to check if the app has opened and show fallback if not
      setTimeout(() => {
        // If the page loses focus, it likely means the app opened
        if (!document.hasFocus()) {
          return; // Exit if the page lost focus
        }
        fallbackVisible.value = true;
        window.location.href = fallbackUrl; // Redirect to fallback URL
      }, 2000); // 2 seconds delay for fallback
    }
  });
  </script>
  
  <style scoped>
  /* Add any necessary styles here */
  #fallback-message {
    margin-top: 20px;
  }
  </style> -->

  <template>
    <div>Hi</div>
  </template>