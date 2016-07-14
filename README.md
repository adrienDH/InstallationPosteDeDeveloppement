Installation d'un poste de développement sur Ubuntu
==

Avoir la résolution maximum sur machine virtuel
--
- Aller dans la barre de menu de la VM > Périphérique > Inséré l'image CD des additions invités
- L'icône du CD devrait apparaître sur le bureau
- Copier Coller le répertoire dans le /home/Pilotes (créer ce répertoire)
- Aller dans ce répertoire
<pre><code>
sudo -s
chmod u+x VBoxLinuxAdditions.run
./VBoxLinuxAdditions.run
</code></pre>
- Redémarrez Ubuntu.

Installer apache 2
--
<pre><code>apt-get install apache2
a2enmod rewrite
sudo service apache2 restart</code></pre>


