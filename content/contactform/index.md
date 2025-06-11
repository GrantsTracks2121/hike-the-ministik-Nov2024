---
title: "Contact Hike The Ministik!"
draft: false
summary: "Contact Hike The Ministik!"
showHero: true
heroStyle: "background"
---
<script src="https://www.google.com/recaptcha/api.js?render=6LfhI10rAAAAAPjMj_r7RycX5lBBzy3n08XckxJI"></script>
<script>
  function onSubmit(event) {
    event.preventDefault(); // Prevent default form submission
    grecaptcha.ready(function() {
      grecaptcha.execute('6LfhI10rAAAAAPjMj_r7RycX5lBBzy3n08XckxJI', {action: 'submit'}).then(function(token) {
        // Add the token to a hidden input field in your form
        document.getElementById('g-recaptcha-response').value = token;
        // Now submit your form
        document.getElementById("HikeTheMinistik-contact-form").submit(); // Give your form an ID
      });
    });
  }
</script>
<section class="bg-white dark:bg-gray-900">
  <div class="px-4 mx-auto max-w-screen-md">
      <p class="mb-8 lg:mb-8 font-light text-center text-gray-500 dark:text-gray-400 sm:text-xl">Do you have a suggestion? Did find find something you think needs to be changed? Please fill in all the details below.</p>
     <form id="HikeTheMinistik-contact-form" name="HikeTheMinistik Contact Form" action="#" class="space-y-8" netlify onsubmit="onSubmit(event)">
          <div>
              <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Your email</label>
              <input type="email" id="email" name="email" class="prose shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-500 focus:border-primary-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="name@mailhost.com" required>
          </div>
          <div>
              <label for="subject" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Subject</label>
              <input type="text" id="subject" name="subject" class="prose block p-3 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm focus:ring-primary-500 focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="Summarize your comment or suggestion..." required>
          </div>
          <div class="sm:col-span-2">
              <label for="message" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-400">Your message</label>
              <textarea id="message" name="message" rows="8" class="prose block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg shadow-sm border border-gray-300 focus:ring-primary-500 focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="Leave a comment or suggestion..."></textarea>
          </div>
          <input type="hidden" id="g-recaptcha-response" name="g-recaptcha-response">
          <button type="submit" class="py-3 px-5 text-sm font-medium text-center text-white rounded-lg bg-primary-700 sm:w-fit hover:bg-primary-800 focus:ring-4 focus:outline-none focus:ring-primary-300 dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800">Send message</button>
      </form>
  </div>
</section>