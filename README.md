<html>
    <body>
        <h1>Hai Cantik</>
        <img src="https://c.tenor.com/tIWicdRJ-wQAAAAC/love-you-lots-kiss.gif" />
        <h1>Maafin Aku Dongggg</>
        <button id=btn_mau" onclick="alert('I LOVE YOUUU')">Mau</button>
        <button id=btn_gamau" onmousemover="gamau(this)style"="position:relative">gamau</button>
    </body>
    <script>
        function gamau(id){
            var mau = document.getElementById('btn_mau');
            var i = math.floor(Math.random() * 300) + 1;
            var j = Math.floor(Math.random() * 100) + mau.offsetTop;
            id.style.left = i + "px";
            id.style.top = j + "px";
        }
    </script>
</html>
