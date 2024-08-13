## Mots-clés KOTLIN

### Mots-clés difficiles 

Les mots-clés suivants sont toujours interprétés comme des mots-clés et ne peuvent pas être utilisés comme identificateurs :
- **as** *est utilisé pour les conversions de types.*<br>
	*Spécifie un alias pour une importation*
-	**as?** *est utilisé pour les coulées de type sûr.*
-	**break** *met fin à l’exécution d’une boucle.*
-	**class** *déclare une classe.*
-	**continue** *passe à l’étape suivante de la boucle englobante la plus proche.*
-	**do** *commence une boucle do/while (une boucle avec une postcondition).*
-	**else** *Définit la branche d’une expression if qui est exécutée lorsque la condition est false.*
-	**false** *spécifie la valeur 'false' du type booléen.*
-	**for** *commence une boucle for.*
-	**fun** *déclare une fonction.*
-	**if** *commence une expression if.*
-	**in**
	*Spécifie l’objet itéré dans une boucle for. est utilisé comme opérateur infix pour vérifier qu’une valeur appartient à une plage, à une collection ou à une autre entité qui définit une méthode* 
- 	**contains** *est utilisé dans lorsque des expressions dans le même but. Marque un paramètre de type comme contravariant*
-	**!in** *est utilisé comme opérateur pour vérifier qu’une valeur n’appartient PAS à une plage, une collection ou une autre entité qui définit une méthode.*
-	**contient.** *est utilisé dans lorsque des expressions dans le même but. interface déclare une interface.*
-	**is**
	*Vérifie qu’une valeur a un certain type. est utilisé dans lorsque des expressions dans le même but.*
-	**!is**
	*vérifie qu’une valeur n’a PAS un certain type. est utilisé dans lorsque des expressions dans le même but.*
-	**null** *est une constante représentant une référence d’objet qui ne pointe vers aucun objet.*
-	**object** *déclare une classe et son instance en même temps.*
-	**package** *Spécifie le package du fichier actif.*
-	**return** *Renvoie la fonction englobante ou la fonction anonyme la plus proche.*
-	**super** *fait référence à l’implémentation super-classe d’une méthode ou ’une propriété. Appelle le constructeur SuperClass à partir d’un constructeur secondaire.*
-	**this** *fait référence au récepteur actuel.Appelle un autre constructeur de la même classe à partir d’un constructeur secondaire.*
-	**throw** *lève une exception.*
-	**true** *spécifie la valeur 'true' du type booléen.*
-	**try** *Commence un bloc de gestion des exceptions.*
-	**typealias** *Déclare un alias de type.*
-	**typeof** *est réservé pour une utilisation future.*
-	**val** *Déclare une propriété en lecture seule ou une variable locale.*
-	**var** *Déclare une propriété mutable ou une variable locale.*
-	**when** *commence une expression when (exécute l’une des branches données).*
-	**while** *commence une boucle while (une boucle avec une précondition).*

### Mots-clés souples 
Les mots-clés suivants agissent comme des mots-clés dans le contexte dans lequel ils s’appliquent, et ils peuvent être utilisés comme identificateurs dans d’autres contextes :
-	by
	délègue l’implémentation d’une interface à un autre objet.
	délègue l’implémentation des accesseurs d’une propriété à un autre objet.
-	catch Commence un bloc qui gère un type d’exception spécifique.
-	constructor déclare un constructeur primaire ou secondaire.
-	delegate est utilisé comme cible de site d’utilisation d’annotation.
-	dynamic fait référence à un type dynamique dans le code Kotlin/JS.
-	field est utilisé comme cible de site d’utilisation d’annotation.
-	file est utilisé comme cible de site d’utilisation d’annotation.
-	finally commence un bloc qui est toujours exécuté à la sortie d’un bloc try.
-	get
	Déclare le getter d’une propriété.
	est utilisé comme cible de site d’utilisation d’annotation.
-	import Importe une déclaration d’un autre paquet dans le fichier courant.
-	init démarre un bloc d’initialisation.
-	param est utilisé comme cible de site d’utilisation d’annotation.
-	property est utilisé comme cible de site d’utilisation d’annotation.
-	receiverest utilisé comme cible de site d’utilisation d’annotation.
-	set
	déclare le setter d’une propriété.
	est utilisé comme cible de site d’utilisation d’annotation.
-	setparam est utilisé comme cible de site d’utilisation d’annotation.
-	value avec le mot-clé déclare une classe inline.class
-	where Spécifie les contraintes d’un paramètre de type générique.

### Mots-clés modificateurs 
Les mots-clés suivants agissent comme des mots-clés dans les listes de modificateurs de déclarations, et ils peuvent être utilisés comme identificateurs dans d’autres contextes :
-	abstract marque une classe ou un membre comme abstrait.
-	actual Désigne une implémentation spécifique à la plate-forme dans des projets multiplateformes.
-	annotation déclare une classe d’annotation.
-	companion déclare un objet compagnon.
-	const marque une propriété en tant que constante de compilation.
-	crossinline Interdit les retours non locaux dans une fonction lambda passée à une fonction en ligne.
-	data indique au compilateur de générer des membres canoniques pour une classe.
-	enum déclare une énumération.
-	expect marque une déclaration comme spécifique à la plate-forme, en attendant une implémentation dans les modules de la plate-forme.
-	external marque une déclaration comme implémentée en dehors de Kotlin (accessible via JNI ou en JavaScript).
-	final interdit de passer outre un membre.
-	infix Permet d’appeler une fonction à l’aide de la notation infixe.
-	inline Indique au compilateur d’intégrer une fonction et les lambdas qui lui sont passés sur le site d’appel.
-	inner Permet de faire référence à une instance de classe externe à partir d’une classe imbriquée.
-	internal Marque une déclaration comme visible dans le module courant.
-	lateinit Permet d’initialiser une propriété non nullable en dehors d’un constructeur.
-	noinline Désactive l’incorporation d’une fonction lambda passée à une fonction inline.
-	open Permet de sous-classer une classe ou de remplacer un membre.
-	operator marque une fonction comme surchargeant un opérateur ou mettant en œuvre une convention.
-	out Marque un paramètre de type comme covariant.
-	override Marque un membre en tant que substitution d’un membre Superclass.
-	private Marque une déclaration comme visible dans la classe ou le fichier actuel.
-	protected Marque une déclaration comme visible dans la classe actuelle et ses sous-classes.
-	public Marque une déclaration comme visible n’importe où.
-	reified Marque un paramètre de type d’une fonction en ligne comme accessible au moment de l’exécution.
-	sealed déclare une classe scellée (une classe avec une sous-classe restreinte).
-	suspend Marque une fonction ou une fonction lambda comme étant suspendue (utilisable comme coroutine).
-	tailrec marque une fonction comme tail-recursive (permettant au compilateur de remplacer la récursivité par l’itération).
-	vararg Permet de passer un nombre variable d’arguments pour un paramètre.

### Identifiants spéciaux 
Les identificateurs suivants sont définis par le compilateur dans des contextes spécifiques, et ils peuvent être utilisés comme des identificateurs normaux dans d’autres contextes :
-	field est utilisé à l’intérieur d’un accesseur de propriété pour faire référence au champ de sauvegarde de la propriété.
-	it est utilisé à l’intérieur d’une fonction lambda pour faire référence implicitement à son paramètre.
Opérateurs et symboles spéciaux 
Kotlin prend en charge les opérateurs et les symboles spéciaux suivants :
-	+, , , , - opérateurs mathématiques -*/%
	* est également utilisé pour passer un tableau à un paramètre vararg.
-	=
	opérateur d’affectation.
	permet de spécifier les valeurs par défaut des paramètres.
-	+=, , , , - opérateurs d’affectation augmentés.-=*=/=%=
-	++, - opérateurs d’incrémentation et de décrémentation.--
-	&&, , - opérateurs logiques 'et', 'ou', 'non' (pour les opérations au niveau du bit, utilisez plutôt les fonctions d’infixe correspondantes).||!
-	==, - opérateurs d’égalité (traduits en appels de pour les types non primitifs).!=equals()
-	===, - les opérateurs d’égalité référentielle.!==
-	<, , , - opérateurs de comparaison (traduits en appels de pour les types non primitifs).><=>=compareTo()
-	[, - opérateur d’accès indexé (traduit en appels de et ).]getset
-	!! Affirme qu’une expression n’est pas nullable.
-	?. effectue un appel sécurisé (appelle une méthode ou accède à une propriété si le récepteur n’est pas nullable).
-	?: Prend la valeur de droite si la valeur de gauche est null (opérateur Elvis).
-	:: Crée une référence de membre ou une référence de classe.
-	.., créez des plages...<
-	: Sépare un nom d’un type dans une déclaration.
-	? Marque un type comme nullable.
-	->
	sépare les paramètres et le corps d’une expression lambda.
	Sépare les paramètres et la déclaration de type de retour dans un type de fonction.
	sépare la condition et le corps d’une branche when expression.
-	@
	introduit une annotation.
	Introduit ou fait référence à une étiquette de boucle.
	introduit ou fait référence à une étiquette lambda.
	fait référence à une expression 'this' à partir d’une portée externe.
	fait référence à une superclasse externe.
-	; sépare plusieurs déclarations sur la même ligne.
-	$ Fait référence à une variable ou à une expression dans un modèle de chaîne.
-	_
	substitue un paramètre inutilisé dans une expression lambda.
	substitue un paramètre inutilisé dans une déclaration de déstructuration.
