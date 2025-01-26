<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Helping Hands Organisation</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css">
</head>
<body class="bg-gray-100 font-sans leading-normal tracking-normal">
    <!-- Header Section -->
    <header class="bg-blue-600 text-white">
        <div class="container mx-auto p-5 flex justify-between items-center">
            <h1 class="text-3xl font-bold">Helping Hands NGO</h1>
            <nav>
                <ul class="flex space-x-6">
                    <li><a href="#about" class="hover:underline">About Us</a></li>
                    <li><a href="#projects" class="hover:underline">Projects</a></li>
                    <li><a href="#team" class="hover:underline">Team</a></li>
                    <li><a href="#contact" class="hover:underline">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-cover bg-center h-screen" style="background-image: url('https://www.bing.com/images/search?view=detailV2&ccid=UK1NnAdU&id=0595C539E7DFF8E35E539781E96625FDB17122A5&thid=OIP.UK1NnAdUN3MeUwywk8VU3AHaE7&mediaurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR.50ad4d9c075437731e530cb093c554dc%3frik%3dpSJxsf0lZumBlw%26riu%3dhttp%253a%252f%252f2.bp.blogspot.com%252f-k8fnLz8XfaY%252fVl3Nngc-17I%252fAAAAAAAAKE8%252fopnWoUxLWDE%252fs1600%252fsmilesquared%25252Bcom.jpg%26ehk%3dxbnkpFLXo8ixomYde5RFw092bgtpptT6xVLXNQ8KFN8%253d%26risl%3d%26pid%3dImgRaw%26r%3d0&exph=1066&expw=1600&q=poor+kids&simid=608055370237302312&FORM=IRPRST&ck=38F2C39AE04F5E941CBDABCC6BA2F13E&selectedIndex=68&itb=0&ajaxhist=0&ajaxserp=0.png/1500x800');">
        <div class="bg-cover:black bg-opacity-80 h-full flex flex-col justify-center items-center text-black">
            <h2 class="text-4xl md:text-6xl font-bold mb-6">Making the World a Better Place</h2>
            <p class="text-lg md:text-xl mb-6">Join us in our mission to uplift and empower communities in need.</p>
            <a href="#contact" class="bg-yellow-500 hover:bg-yellow-600 text-white py-3 px-6 rounded-lg text-lg">Get Involved</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-white">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-6">About Us</h2>
            <p class="text-gray-700">Helping Hands is a non-profit organization dedicated to improving the lives of underprivileged communities through education, healthcare, and empowerment initiatives.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-16 bg-gray-100">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-6">Our Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-white rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">Education for All</h3>
                    <p class="text-gray-600">Providing access to quality education for children in rural areas.</p>
                </div>
                <div class="bg-white rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">Healthcare Camps</h3>
                    <p class="text-gray-600">Organizing free health check-ups and awareness campaigns.</p>
                </div>
                <div class="bg-white rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">Women Empowerment</h3>
                    <p class="text-gray-600">Promoting self-reliance and skills training for women.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Team Section -->
    <section id="team" class="py-16 bg-white">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-6">Meet Our Team</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-gray-100 rounded-lg shadow-lg p-6">
                    
                    <h3 class="text-xl font-bold">Cristiano Ronaldo</h3>
                    <p class="text-gray-600">Founder</p>
                </div>
                <div class="bg-gray-100 rounded-lg shadow-lg p-6">
                   
                    <h3 class="text-xl font-bold">Mihir Dedania</h3>
                    <p class="text-gray-600">Project Manager</p>
                </div>
                <div class="bg-gray-100 rounded-lg shadow-lg p-6">
                  
                    <h3 class="text-xl font-bold">Darshan Mahida</h3>
                    <p class="text-gray-600">Volunteer Coordinator</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-100">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-6">Contact Us</h2>
            <p class="text-gray-700 mb-6">Have questions or want to get involved? Reach out to us!</p>
            <form action="#" method="POST" class="max-w-xl mx-auto">
                <div class="mb-4">
                    <input type="text" name="name" placeholder="Your Name" class="w-full p-3 rounded-lg border-gray-300">
                </div>
                <div class="mb-4">
                    <input type="email" name="email" placeholder="Your Email" class="w-full p-3 rounded-lg border-gray-300">
                </div>
                <div class="mb-4">
                    <textarea name="message" placeholder="Your Message" rows="5" class="w-full p-3 rounded-lg border-gray-300"></textarea>
                </div>
                <button type="submit" class="bg-blue-600 hover:bg-blue-700 text-white py-3 px-6 rounded-lg">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-blue-600 text-white py-4">
        <div class="container mx-auto text-center">
            <p>&copy; 2025 Helping Hands Org. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
