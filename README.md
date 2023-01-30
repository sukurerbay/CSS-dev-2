# CSS-dev-2
Google Ana Sayfasını Tasarlamak
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
      <img src="images/google.jpg" alt="Logo" />
      <table>
        <tr>
          <td class="search-box">
            Search the web using Google!
            <br />
            <input type="text" id="search-box" name="search-box"  value size="40" /><br />
            <input type="submit" value="Google Search" />
            <input type="submit" value="I'm feeling lucky!" />
          </td>
        </tr>
      </table>
      <table>
        <tbody>
          <tr>
            <td class="box1">
              Special Searches
              <br />
              <a href="https://www.stanford.edu/search/">Stanford Search</a>
              <br />
              <a href="https://www.plesk.com/blog/various/find-files-in-linux-via-command-line/">Linux Search</a>
            </td>
            <td class="box2">
              <a href="https://support.google.com/">Help!</a><br />
              <a href="https://about.google/">About Google!</a><br />
              <a href="https://www.google.com/search?q=Company+Info&oq=Company+Info&aqs=chrome..69i57j0i67j0i512l3j0i22i30l5.1818j0j15&sourceid=chrome&ie=UTF-8">Company Info</a><br />
              <a href="https://tr.wikipedia.org/wiki/Google">Google! Logos</a></td>
            <td class="box3">
              <p>Get Google</p><br />
              <p>updates monthly:</p><br />
              <input type="text" value="your e-mail" /><br />
              <input type="submit" value="Subscribe" />
              <a href="https://archive.org/"
                >Archive</a>
            </td>
          </tr>
        </tbody>
      </table>
      <br />
      <footer>Copyright &#169;1998 Google Inc.</footer>
    </div>
  </body>
</html>
