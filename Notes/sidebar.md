<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Alignment Example</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="../pages.css">
</head>

<body>

    <div class="layout">
        <!-- Sidebar -->
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <a class="navbar-brand d-lg-none" href="#">Menu</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSidebar" aria-controls="navbarSidebar" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSidebar">
                <div class="sidebar">
                    <div class="sidebar-section">
                        <button class="accordion">Getting started <i class="fa-solid fa-chevron-down"></i></button>
                        <div class="panel">
                            <a href="/pages/forms/box.html">Introduction</a>
                            <a href="#">Download</a>
                            <a href="#">Contents</a>
                            <a href="#">Browsers & devices</a>
                            <a href="#">JavaScript</a>
                        </div>
                    </div>

                    <div class="sidebar-section">
                        <button class="accordion">Layout <i class="fa-solid fa-chevron-down"></i></button>
                        <div class="panel">
                            <a href="">Breakpoints</a>
                            <a href="">Containers</a>
                            <a href="">Grid</a>
                            <a href="">Columns</a>
                            <a href="">Gutters</a>
                            <a href="">Utilities</a>
                            <a href="">Z-index </a>
                        </div>
                    </div>

                    <div class="sidebar-section">
                        <button class="accordion">Content <i class="fa-solid fa-chevron-down"></i></button>
                        <div class="panel">
                            <a href="">Typography</a>
                            <a href="">Images</a>
                            <a href="">Tables</a>
                            <a href="">Figures</a>
                        </div>
                    </div>

                    <div class="sidebar-section">
                        <button class="accordion">Forms <i class="fa-solid fa-chevron-down"></i></button>
                        <div class="panel">       
                            <a href="">Overview</a>
                            <a href="">Form control</a>
                            <a href="">Select</a>
                            <a href="">Checks & radios</a>
                            <a href="">Range</a>
                            <a href="">Input group</a>
                            <a href="">Floating labels</a>    
                            <a href="">Layout</a>  
                            <a href="">Validation</a>              

                        </div>
                    </div>

                    <div class="sidebar-section">
                        <button class="accordion">Components <i class="fa-solid fa-chevron-down"></i></button>
                        <div class="panel">
                            <a href="">Alerts</a>
                            <a href="">Buttons</a>
                            <a href="">Button group</a>
                            <a href="">Card</a>
                            <a href="">Carousel</a>
                            <a href="">Close button</a>
                            <a href="">Collapse</a>
                            <a href="">Dropdowns</a>
                            <a href="">List group</a>
                            <a href="">Modal</a>
                            <a href="">Navs & tabs</a>
                            <a href="">Navbar</a>
                            <a href="">Pagination</a>
                        </div>
                    </div>
                </div>
            </div>
        </nav>

        <!-- Main Content -->
        <div class="main-content">


















            
    </div>
    
    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

    <script>
        var accordions = document.getElementsByClassName("accordion");

        for (var i = 0; i < accordions.length; i++) {
            accordions[i].addEventListener("click", function() {
                this.classList.toggle("active");
                var panel = this.nextElementSibling;
                if (panel.style.display === "block") {
                    panel.style.display = "none";
                } else {
                    panel.style.display = "block";
                }
            });
        }
    </script>

</body>

</html>
