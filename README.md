<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MutantPunks - Self Inscribe Collection</title>
  <link rel="icon" type="image/x-icon" href="favicon.ico">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css"
    integrity="sha512-wnea99uKIC3TJF7v4eKk4Y+lMz2Mklv18+r4na2Gn1abDRPPOeef95xTzdwGD9e6zXJBteMIhZ1+68QC5byJZw=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

  <link href="https://fonts.cdnfonts.com/css/edit-undo-brk" rel="stylesheet">

</head>

<body>

  <div id="home"></div>
  <nav class="backdrop-filter backdrop-blur-md sticky z-50 top-0">
    <div class=" flex flex-wrap items-center justify-between mx-auto p-4">
      <a href="#home" class="flex">
        <img src="./MutantPunks-Name.png" class="h-16 nav-button" />
      </a>

    </div>
  </nav>

  <div id="how-to" class="main">
    <div class=" hello text-center text-3xl md:text-4xl lg:text-6xl "> 10000 MutantPunks, first is first!</div>
    <div class=" hello text-center text-3xl md:text-4xl lg:text-6xl "> -</div>
    <div class=" hello text-center text-3xl md:text-4xl lg:text-4xl "> 10000 Minted!</div>
    <br>
    <button class="accordion text-2xl font-large">How to</button>
    <div class="panel">
      <br>
      <li>The Order is a self incribe collection, only the first confirmed inscription of each image is counted as part
        of the collection.</li>
      <li>You can check a MutantPunks availability by using the check button below its image. <a
          style="color:#d43737;">NOTE:
          This doesnt include any unconfirmed inscriptions, you can check unconfirmed inscriptions on <a
            class="font-bold" target="_blank" href="https://unisat.io/" style="color:#f83f3f; ">Unisat </a></a></li>
      <li>The status of the MutantPunk will appear on the bottom right of the page, if its free; right click save and
        inscribe using your favourite service.</li>
      <li>Confirmed Taken MutantPunks will appear greyed out, updates on confirmed taken MutantPunks will happen
        periodically
      </li>
      <li>Always use the check button as some MutantPunks will be inscribed but not be confirmed taken</li>

    </div>
  </div>

  <div id="toastBox"></div>
  <div id="the-toshis" class="main">
    <br>
    <div class="products grid grid-cols-3 md:grid-cols-7 lg:grid-cols-9 xl:grid-cols-10 pt-6 gap-6 px-10"
      id="thumbnails">

    </div>
  </div>
  <br>
  <div class="navnum text-center" id="nav"></div>

  <footer class="feeter">
    <img src="Toshi-GM.gif" class="home-img">
    <p class="text-2xl">Powered by <a href="https://twitter.com/sat_toshis" target="_blank">Toshi</a></p>
  </footer>

  <script src="script.js"></script>
</body>

</html>
