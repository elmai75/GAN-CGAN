# BE GAN & CGAN ELMAI MOHAMED
### GAN (Generative Adversarial Network) est un type d'algorithme d'apprentissage profond qui utilise deux réseaux neuronaux, un générateur et un discriminant, pour générer des données simulées qui sont similaires à des données réelles. Le générateur crée des données simulées à partir d'un bruit aléatoire, tandis que le discriminant évalue si les données sont réelles ou simulées :

 
  * L'entraînement du GAN consiste en une compétition entre le générateur et le discriminant. Le générateur essaie de tromper le discriminant en lui faisant croire que les données simulées sont réelles, tandis que le discriminant essaie de distinguer les données réelles des données simulées. Au fil du temps, le générateur devient plus habile à créer des données qui peuvent tromper le discriminant, ce qui conduit à la production de données simulées de plus en plus réalistes.

  * CGAN (Conditional Generative Adversarial Network) est une extension du GAN qui permet de contrôler la génération de données simulées en ajoutant des conditions ou des étiquettes spécifiques. Par exemple, un CGAN peut être entraîné pour générer des images de chiffres manuscrits en fonction d'une étiquette spécifique de chiffre donnée en entrée. Cela permet de créer des données simulées plus précises et contrôlées en fonction des conditions données en entrée.

  Ce BE decopose en deux parties:

  * Partie1-DCGAN : L'objetcif de cette partie c'est de comprendre les bases de DCGAN et de generere des chiffres manuscrits avec la re-entrainement de modèle