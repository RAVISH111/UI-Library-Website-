<!-- -------------navbar html code------------- -->
<header>
        <nav class="navbar navbar-expand-lg navbar-light sidebar-margin">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">
                    <img src="../../assets/logo.png" alt="Logo" width="50">
                </a>
                <!-- Navbar Toggler Button -->
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link active an" aria-current="page" href="../../index.html">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Blogs</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Documentation</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                Components
                            </a>
                            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <li><a class="dropdown-item" href="#">Button</a></li>
                                <li><a class="dropdown-item" href="#">Text</a></li>
                            </ul>
                        </li>
                    </ul>
                    <form class="d-flex">
                        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    </form>
                </div>
            </div>
        </nav>
</header>





<!-- ------------navbar css here ------------ -->

header {
    background-color: #309794;
    margin: 0 auto;
    text-align: center;
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 1000; /* Ensures navbar stays above other elements */
}

.navbar {
    padding: 10px;
}

.navbar-toggler {
    border-color: #ddd;
}

.navbar-toggler-icon {
    color: #333;
}

nav img {
    width: 3.5rem;
}

.support-section {
    max-width: 1000px;
    margin: 0 auto;
    padding: 1rem;
    text-align: center;
    text-align: center;
}

.support-section h2 {
    margin-bottom: 20px;
    font-size: 1.5rem;
    color: #008080; /* Optional: match the color to the theme */
    letter-spacing: 0.1em;
}

.logo-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
}

.logo-item {
    flex: 2 2 250px; /* Flex-basis allows wrapping and ensures items are responsive */
    max-width: 200px; /* Maximum width for larger screens */
}

.logo-item img {
    width: 100%;
    height: auto;
}
.layout{
    margin-top: 4.5rem;
}




<!-- --------focus here for inplement--------  -->

manage your page  put in main page --> margin-top:4.5rem;
for sidebar in media query create .sidebar{ margin-top: 20px;}