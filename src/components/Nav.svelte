<nav>
    <div class="left">
        <ul class="nav-links">
            <li> <a href="/">Home</a> </li>
            <li> <a href="/Guides">Guides</a> </li>
            <li> <a href="/Blog">Blog</a> </li>
            <li> <a href="/Premium">Premium</a> </li>
        </ul>
    </div>

    <div class="right">
        <ul class="nav-links">
            <li> <a href="/Login">Login</a> </li>
            <li> <a href="/Signup">Signup</a> </li>
        </ul>
    </div>
</nav>

<style>
    nav {
        display: block;
        height: 5em;
    }
    div.left {
        float: left
    }

    div.right {
        float: right
    }
    .nav-links {
        list-style: none;
        padding: 5px;
        display:flex;
        flex-wrap: nowrap;
        flex-direction: row;
    }
    .nav-links li {
        margin: 0px 0.5em;
    }
</style>