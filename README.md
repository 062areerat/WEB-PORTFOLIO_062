<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-900 text-white font-sans">

    <nav class="flex justify-between items-center px-10 py-4 bg-[#29b6f6]">
        <h1 class="text-xl font-bold">Areerat Promkul</h1>
        <ul class="flex space-x-6">
            <li><a href="#" class="hover:text-gray-300">Home</a></li>
            <li><a href="#" class="hover:text-gray-300">About</a></li>
            <li><a href="ex5_cloning website.html" class="hover:text-gray-300">Cloning Website</a></li>
            <li><a href="#" class="hover:text-gray-300">Contact</a></li>
        </ul>
    </nav>

    <section class="flex flex-col items-center text-center py-16 px-6">
        <h2 class="text-3xl font-bold bg-[#29b6f6] px-4 py-2 rounded-lg inline-block">Welcome To</h2>
        <h1 class="text-5xl font-bold mt-4">Web Portfolio</h1>
        <p class="text-lg mt-2">6640011062 Areerat Promkul</p>

        <!-- Profile Image -->
        <div class="relative mt-8">
            <div class="w-64 h-64 rounded-full overflow-hidden border-4 border-white shadow-lg">
                <img src="images1.png" alt="Profile Image" class="w-full h-full object-cover">
            </div>
            <div class="absolute bottom-0 right-0 bg-white rounded-full p-3 shadow-md">
                <img src="https://cdn-icons-png.flaticon.com/512/1041/1041916.png" alt="Globe Icon" class="w-10 h-10">
            </div>
        </div>
    </section>
    <section class="px-10">
        <!-- Five Content Boxes in a single row -->
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-5 gap-6 mt-8">
            <!-- Box 1 -->
            <a href="ex1_menu.html" class="flex flex-col items-center bg-[#29b6f6] rounded-lg p-4 shadow-lg">
                <img src="https://static.thairath.co.th/media/dFQROr7oWzulq5Fa4MvAZOQmFYm5g8AjQ0hEomarKgOcnnBBWaFW3Ti6Wz9daIWqWz0.jpg"
                    alt="Menu" class="w-full h-32 object-cover rounded-lg">
                <p class="mt-2 text-white font-bold">Menu</p>
            </a>
    
            <!-- Box 2 -->
            <a href="ex2_form.html" class="flex flex-col items-center bg-[#29b6f6] rounded-lg p-4 shadow-lg">
                <img src="https://t3.ftcdn.net/jpg/05/17/56/84/360_F_517568495_mgn7HoUgjFFDUFzBbmxOC5B7IwV6NXA9.jpg"
                    alt="Form" class="w-full h-32 object-cover rounded-lg">
                <p class="mt-2 text-white font-bold">Form</p>
            </a>
    
            <!-- Box 3 -->
            <a href="ex3_box model.html" class="flex flex-col items-center bg-[#29b6f6] rounded-lg p-4 shadow-lg">
                <img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcQB7Fl0Xd149ULYbyWcML3qPRKSu9vpW81yJ3YebqfjI8ptxHjR"
                    alt="Box Model" class="w-full h-32 object-cover rounded-lg">
                <p class="mt-2 text-white font-bold">Box Model</p>
            </a>
    
            <!-- Box 4 -->
            <a href="ex4_page layout.html" class="flex flex-col items-center bg-[#29b6f6] rounded-lg p-4 shadow-lg">
                <img src="https://f.ptcdn.info/568/018/000/1399269267-1236910102-o.jpg" alt="Page Layout"
                    class="w-full h-32 object-cover rounded-lg">
                <p class="mt-2 text-white font-bold">Page Layout</p>
            </a>
    
            <!-- Box 5 -->
            <a href="ex5_cloning website.html" class="flex flex-col items-center bg-[#29b6f6] rounded-lg p-4 shadow-lg">
                <img src="https://plantorchid.wordpress.com/wp-content/uploads/2017/02/blue-mystique-orchid.jpg" alt="Cloning Website"
                    class="w-full h-32 object-cover rounded-lg">
                <p class="mt-2 text-white font-bold">Cloning Website</p>
            </a>
        </div>
    </section>
    
