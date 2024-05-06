

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


<div align="center" style="width: 100%; text-align: center; font-size: 18px;  margin-top: 20px; margin-bottom: 20px">
<p style="font-size: 12px; margin: 0;text-align: center"> GET / </p>
<h2 style="text-align: center">Hey, soy Eliezer</h2>
</div>

<div align="center" style="display:flex; gap: .25rem; justify-content: center; flex-wrap: wrap; margin-block: 1rem">

<img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" alt="Flutter" />

<img src="https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React Native" />    

<img src="https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white" alt="AMgular" />
    
<img src="https://img.shields.io/badge/astro-%232C2052.svg?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" />

<img src="https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white" alt="Go (Golang)" />                

<img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJs" />
</div>

<!-- ![Lenguajes Top](https://github-readme-stats.vercel.app/api/top-langs?username=ttmday&layout=compact&theme=dark)
 -->

#### También puedes encontrarme en
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ttmday)

#### Algunos de mis proyectos actuales
<a title="Gogh Creative Page" target="_blank" href="https://gogh.flippoapp.com">
<img src="./gogh.jpg" alt="Gogh Creative"
width="180px"
height="auto"
/>
</a>
<a title="Shurupitos App" target="_blank" href="https://play.google.com/store/apps/details?id=com.gogh.shurupitos">
<img src="./icn-shurupitos-app1.png" alt="Shurupitos"
width="180px"
height="auto"
/>
</a>
