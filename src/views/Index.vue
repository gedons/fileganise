<template>
  <div class="flex flex-col min-h-screen">
    <!-- Header -->
    <header class="bg-blue-600 text-white py-4 shadow-lg">
      <div class="container mx-auto px-4">
        <h1 class="text-3xl font-bold">Welcome to My File Organizer</h1>
        <p class="mt-2 text-lg">Organize, manage, and access your files and folders with ease</p>
      </div>
    </header>

    <!-- Main Content -->
    <main class="flex-1">
      <div class="container mx-auto px-4 py-8">
        <section>
          <h2 class="text-2xl font-semibold mb-4">About This Site</h2>
          <p class="text-gray-700 mb-4">
            Our file organizer application allows you to efficiently manage your digital files and folders. 
            With our intuitive interface, you can easily upload, create, delete, and organize your files and 
            folders in a way that suits your needs. Whether you're working with documents, images, or other 
            file types, our platform offers a seamless experience to keep everything in order.
          </p>
          <p class="text-gray-700">
            Features include:
            <ul class="list-disc pl-5">
              <li>File uploading with drag-and-drop functionality</li>
              <li>Folder creation and management</li>
              <li>File preview and access in various formats</li>
              <li>Secure authentication to protect your data</li>
              <li>Intuitive grid and list view options</li>
            </ul>
          </p>
        </section>
      </div>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-4 mt-8">
      <div class="container mx-auto px-4">
        <p class="text-center">&copy; 2024 My File Organizer. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'Index',
};
</script>

<style scoped>
/* Custom styles can go here */
</style>
