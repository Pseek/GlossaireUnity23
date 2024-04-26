## Unity Life Cycle
Awake : Une methode qui est appéler au chargement de l'objet et ne dois pas faire attention au reste
	```public void Awake()
	{
		Debug.Log("Le Script se fait au chargement de lui-meme")
	}```

Start :Une méthode qui est appelée au chargement de l'objet et qu'il doit faire attention au reste
	```public void Start()
	{
		Debug.Log("Le Script se fait après l'Awake de tout le monde")
	}```

Update : une méthode qui se lance à chaque frame graphique
	```public void Update()
	{
		Debug.Log("Le Script se fait à chaque frame")
	}```
FixedUpdate : Une méthode qui se lance à chaque frame moteur
	```public void FixedUpdate()
	{
		Debug.Log("Le Script se fait à chaque frame moteur")
	}```
LateUpdate : une méthode qui se lance à la fin de la frame
	```public void LateUpdate()
	{
		Debug.Log("Le Script se fait à la fin de la frame")
	}```
OnEnable : Une méthode qui active l'objet
	```public void OnEnable()
	{
		Debug.Log("Le Script est activé")
	}```
OnDisable : une méthode qui désacvite l'objet
	```public void OnDisable()
		{
			Debug.Log("Le Script est désactivé")
		}```
OnDrawGizmos :