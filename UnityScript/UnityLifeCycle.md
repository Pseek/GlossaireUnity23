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
LateUpdate : une méthode qui se lance après la méthode Update
	```public void LateUpdate()
	{
		Debug.Log("Le Script se fait après la méthode Update")
	}```
OnEnable : Une méthode qui s'active lorsque l'objet est activé
	```public void OnEnable()
	{
		Debug.Log("L'objet est activé")
	}```
OnDisable : une méthode qui s'active lorsque l'objet est desactivé
	```public void OnDisable()
		{
			Debug.Log("L'objet est désactivé")
		}```
OnDrawGizmos :