

```go

func main() {

  	router := http.NewServeMux()

	router.HandleFunc("/", func(w http.ResponseWriter, r *http.Request) {
		json.NewEncoder(w).Encode(map[string]interface{}{
			"message": "Hey, soy Eliezer",
		})
	})

	http.ListenAndServe(":8080", router)
}

```


<div style="width: 100%; text-align: center; font-size: 18px;  margin-top: 20px; margin-bottom: 20px">
<p style="font-size: 12px; margin: 0;text-align: center"> GET / </p>
<span style="text-align: center">Hey, soy <strong style="font-size: 20px">Eliezer</strong></span>
</div>

<div style="display:flex; gap: .25rem; justify-content: center; flex-wrap: wrap; margin-block: 1rem">

<img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" alt="Flutter" />

<img src="https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React Native" />    

<img src="https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white" alt="AMgular" />
    
<img src="https://img.shields.io/badge/astro-%232C2052.svg?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" />

<img src="https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white" alt="Go (Golang)" />                

<img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJs" />
</div>

<!-- ![Lenguajes Top](https://github-readme-stats.vercel.app/api/top-langs?username=ttmday&layout=compact&theme=dark)
 -->
