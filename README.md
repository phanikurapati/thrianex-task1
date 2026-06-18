body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header,
main,
footer {
    padding: 20px;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    gap: 15px;
}

a {
    text-decoration: none;
}

.skip-link {
    position: absolute;
    left: -9999px;
}

.skip-link:focus {
    left: 10px;
    top: 10px;
}

:focus {
    outline: 3px solid black;
    outline-offset: 2px;
}
