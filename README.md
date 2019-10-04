# javascript-code-to-load-later
simple inline javascript code to load later in html body - dom


<body>
<!-- <script src="js/main.js"></script> -->
    <script type="text/javascript">
        window.addEventListener("load", function() {
            const script = document.createElement('script');
            script.src = "js/main.js";
            document.body.appendChild(script);
        });    
    </script>
</body>
