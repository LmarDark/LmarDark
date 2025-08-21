<div align="center">
<h1>Hi there, I'm Lucas <img  src="https://camo.githubusercontent.com/0c732027af8a28d138e3698181f7be7c9b97d443b4beb9c7ce8ec4cffc6b4767/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f6876524a434c467a6361737252346961377a2f67697068792e676966" width="3%"></img></h1>
</div>

<div align="center">
<h3>🙎 Lucas Matheus | 💻 Back-end developer | 🛸 Brazil</h3>
</div>

<div align="center">
 <a href="https://www.linkedin.com/in/lucas-matheus-alves-rodrigues-509b1a240/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
 <a href = "mailto:lucasmatheusalero@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
 <a href="https://www.instagram.com/https_lmar/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
</div>

<div align="center">
 ⚡️ <i>I don't trust people who don't indent their code properly</i> ⚡️
</div>
 
<hr>

```php
?php
    $class = new LmarDark;

    $person = $class->create();
    echo "Name: "."$person->name";
    echo "\nAge: "."$person->age\n";
    echo "Languages: ";

    $count = 0;
    foreach($person->langs as $language) {
        $count++;


        if(count($person->langs) == $count) {
            echo $language;
            return;
        }

        echo "$language, ";
    }

    class LmarDark {
        public string $name;
        public int $age;

        public function create() {
            $person = new stdClass();

            $person->name = 'Lucas Matheus';
            $person->age = 22;
            $person->langs = [
                "PHP",
                "MySQL",
                "PostgreSQL",
                "HTML",
                "CSS",
                "Python",
                "Go",
                "Shell Script",
                "Vue"
         ];

            return $person;
        }
    }

```

---
<h2>💡 Languages</h2>
<p>
  <img src="https://skillicons.dev/icons?i=php,js,ts,html,css,py,go,mysql,postgres,bash,yaml,md"/>
</p>

<h2>⚙️ Technologies</h2>
<p>
  <img src="https://skillicons.dev/icons?i=laravel,vuejs,tailwind,docker,kubernetes,redis,nginx,vite&theme=dark"/>
</p>

<h2>🛠 Tools</h2>
<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,figma,postman&theme=dark"/>
</p>

<h2>🌍 Environment</h2>
<p>
  <img src="https://skillicons.dev/icons?i=linux,vim,vscode,docker,kubernetes,nginx,git&theme=dark"/>
</p>

<h2>📊 GitHub Stats</h2>
<p>
  <img src="https://github-readme-stats.vercel.app/api?username=lmardark&show_icons=true&theme=dark" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lmardark&layout=compact&theme=dark" alt="Top Langs"/>
</p>

---

<!--<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lmardark&layout=donut&locale=pt-br&theme=dark&hide_border=true&border_radius=20">
</p>-->




