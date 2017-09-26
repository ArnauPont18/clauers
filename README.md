# clauers
Per aprende l'us del github


----------------------------------------------------------------
Per treballar localment serveix per descarregar-se software i modificar-lo localment, fent copies de les diferents versions:

    Instal·lar-lo: https://git-for-windows.github.io/
    git clone                                                  Clona el repositori i fa una carpeta amb el nom del repositori et baixa tots el arxius
    git pull                                                      Actulitza la clonació cal estar a dintre del directori
    git add nom_arxiu                                     Amb aquesta orde afegim un arxiu al repositori local.
    git status                                                 Permet veure si tinguem els arxius actualitzats al commit o versió o no.
    git commit "comentari ...... comentari"        creen una nova versió, sempre es pot tornar a una versió antiga. Serveix per un control de les versions. Quan es programa es fa una variació, vegem que aquesta variació funciona es guarda i sempre es pot tornar a questa versió. El comentari es obligatori
    git status                                                 Permet veure si tinguem els arxius actualitzats al commit o versió o no.

Per treballar remotament. Cal donar-se de alta al github. Una vegada donats d'alta podem crear els nostres repositoris i el mes interessant participar amb els repositoris dels demes.

    Donar-se d'alta.
    Fer  un fork del repositori clauers amb el que volem treballar amb el nostre compte( des de el compte del professor que ja sigueu usuaris.
    Fer un git clone des el el vostre compte del repositori caluers.
    Crear una carpeta amb el vostre nom al repositori clauers i afegir els clauer en format original(solidworks, freecad...) en .step i en .stl

[ videos 5 i 6]

git config user.mail "vostre_correu@gmail.com"

git config user.name "usuari git-hub"

    git status                       Ens dirà que tinc arxius i carpetes no afegides(la carpeta i el clauer).
    git add  /carpeta usuari/arxiuclauer.stl                    Afegir el arxiu stl
    git add /carpeta usuari/arxiucaluer.step                 Afegit el arxiu step
    git add /carpeta usuari/arxiuclauer.formatOrigial           Afegeix l'arxiu solid works freecad...
    git add /carpeta usuari/*      Els afegiria tots a la vegada
    git status           Ens dirà que ja hem afegit els arxius i aixó vol que hi ha canvis que es una nova versió del repositori clauers
    git commit -m "esta es la meva aprotacio als clauers"
    git status      veurem que ja esta dessada la nova versió i que anem una versió per davant del clauer
    git push origin master      Ens demanar el nom del github i el usuari
    Si anem a la web hit-gub ja podrem veure el nostre clauer al nostre compte.

[ video 7]

    Fer un pull request. Cal anar a la pàgina hitgub i al simbol verd de l'esquerra fas un pull-request. (Si no ho troves visualitza el video 7).

[ video 8]

    Sincronitzar el nostre repositori amb el del master.



