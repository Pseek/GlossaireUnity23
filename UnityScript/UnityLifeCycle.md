## Unity Life Cycle
Awake : Une methode qui est app�ler au chargement de l'objet et ne dois pas faire attention au reste
	```public void Awake()
	{
		Debug.Log("Le Script se fait au chargement de lui-meme")
	}```

Start :Une m�thode qui est appel�e au chargement de l'objet et qu'il doit faire attention au reste
	```public void Start()
	{
		Debug.Log("Le Script se fait apr�s l'Awake de tout le monde")
	}```

Update : une m�thode qui se lance � chaque frame graphique
	```public void Update()
	{
		Debug.Log("Le Script se fait � chaque frame")
	}```
FixedUpdate : Une m�thode qui se lance � chaque frame moteur
	```public void FixedUpdate()
	{
		Debug.Log("Le Script se fait � chaque frame moteur")
	}```
LateUpdate : une m�thode qui se lance apr�s la m�thode Update
	```public void LateUpdate()
	{
		Debug.Log("Le Script se fait apr�s la m�thode Update")
	}```
OnEnable : Une m�thode qui s'active lorsque l'objet est activ�
	```public void OnEnable()
	{
		Debug.Log("L'objet est activ�")
	}```
OnDisable : une m�thode qui s'active lorsque l'objet est desactiv�
	```public void OnDisable()
		{
			Debug.Log("L'objet est d�sactiv�")
		}```
OnDrawGizmos :