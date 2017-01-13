#  <span style="color: #fb4141">**Bytecode Java **</span> 

<p>&nbsp; </p>

<p style="text-align:right";><span style="color: #0000FF"> Mamady SAMASSA TSI-G-2016-2017</span></p>

> ### <span style="color: #0000FF">Definition</span>
- Bytecode java ou encore code binaire (Java pseudo-code) en français, est un code intermédiaire entre le code source et le code machine exécutable, issu de la compilation d'un fichier écrit en code source Java, et qui est traité dans la machine virtuelle Java.  <p>&nbsp; </p>
- Ce code particulier se trouve dans les fichiers précompilés du programme; en Java, un fichier source a pour extension . java et un fichier précompilé a l'extension .class : c'est dans ce dernier que ce trouve le byte code.

<p>&nbsp; </p>

> ### <span style="color: #0000FF">Bytecode & JVM</span>
- Les programmes Java sont, avant d'être utilisés par la machine virtuelle, précompilés en bytecode (par l'IDE ou à la main). Ce bytecode n'est compréhensible que par une JVM, et c'est celle-ci qui va faire le lien entre ce code et la machine.  <p>&nbsp; </p>
- La machine virtuelle Java (en anglais Java virtual machine, abr. JVM) est un appareil informatique fictif qui exécute des programmes compilés sous forme de bytecode Java. L'appareil est simulé par un logiciel spécifique à chaque plate-forme ou couple (machine/système d’exploitation) et permet aux applications Java compilées en bytecode de produire les mêmes résultats quelle que soit la plate-forme, tant que celle-ci est pourvue de la machine virtuelle Java adéquate.(Wikipedia).  <p>&nbsp; </p>
- Elle exécute les instructions données par le bytecode contenu dans la classe java en suivant le modèle de la pile : chaque niveau de pile contient les données propres à chaque opération. <p>&nbsp; </p>
- Elle (la machine virtuelle Java) se présente différemment selon qu'on se trouve sous Mac, sous Linux ou encore sous Windows. Par contre, le byte code, lui, reste le même quel que soit l'environnement avec lequel a été développé et précompilé le programme Java. Ce qui a comme conséquence directe : quel que soit l'OS sous lequel a été codé un programme Java, n'importe quelle machine pourra l'exécuter si elle dispose d'une JVM.

<p>&nbsp; </p>

> ### <span style="color: #0000FF">Schema explicatif du mecanisme</span>
![](/home/prof/Bureau/Mamady/Java/msamassa_bytecode_java/Bytecode-block-diagram1.png) 

