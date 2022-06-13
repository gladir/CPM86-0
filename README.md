# CPM86-0
Clone du <a href="https://www.gladir.com/OS/CPM86/intro.htm">CP/M-86</a> écrit en langage de programmation Pascal

<h2>Liste des fichiers</h2>

Voici la liste des différents fichiers proposés dans CPM86-0 :

<table>
		<tr>
			<th>Nom</th>
			<th>Description</th>	
		</tr>
		<tr>
			<td><b>ASM86.PAS</b></td>
			<td>Cette commande permet de lancer le compilateur de langage de programmation assembleur pour les microprocesseur 8086. Cette commande est inspiré de la commande <a href="https://www.gladir.com/OS/CPM86/asm86.htm">ASM86</a> du système d'exploitation CP/M 86.</td>
		</tr>	
     <tr>
			<td><b>CPM86.PAS</b></td>
			<td>Cette commande permet de lancer l'interpréteur de commande du système d'exploitation CP/M-86.</td>
		</tr>
	 	<tr>
			<td><b>ED.PAS</b></td>
			<td>Cette commande permet de lancer l'éditeur en ligne de commande. Cette commande est un clone de la commande ED du système d'exploitation CP/M-86.</td>
		</tr>
		<tr>
			<td><b>SUBMIT.PAS</b></td>
			<td>Cette commande permet d'exécuter un fichier .SUB.</td>
		</tr>
		<tr>
			<td><b>TOD.PAS</b></td>
			<td>Cette commande permet de fixer la date et l'heure d'affichage dans la ligne d'état du bas de l'affichage. Cette commande est inspiré de la commande <a href="https://www.gladir.com/OS/CPM86/tod.htm">TOD</a> du CP/M-86.</td>
		</tr>
</table>

NOTE: La commande EXIT a été ajouté au CPM86.PAS afin de permettre de sortir de l'interpréteur de commande CP/M-86, lequel ne prévoyait pas de sortie.

<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> <i>LEFICHIER.PAS</i></pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> <i>LEFICHIER.PAS</i></pre>
	
Par exemple, si vous voulez compiler CPM86.PAS, vous devrez tapez la commande suivante :

<pre><b>fpc</b> CPM86.PAS</pre>

<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/CPM86-0/blob/main/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/CPM86-0/blob/main/LICENSE">MIT</a>.</li>
</ul>

