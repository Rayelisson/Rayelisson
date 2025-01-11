# 👨🏻‍💻 [Rayelisson Lima]() [@rayelisson]()
🤝 Estou procurando ajuda para aprender sobre Back-End.

[![GitHub followers](https://img.shields.io/github/followers/Rayelisson?label=Follow&style=social)](https://github.com/Rayelisson/?tab=follow)
[![Gmail Badge](https://img.shields.io/badge/-rayelissonl@gmail.com-c14438?style=social&logo=Gmail&logoColor=red&link=mailto:email@anuragsingh.dev)](mailto:rayelissonl@gmail.com)
[![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-blue?style=social&logo=Linkedin&logoColor=blue&link=https://www.linkedin.com/in/rayelisson/)](https://www.linkedin.com/in/rayelisson/)

<img align="right" width="330" src="https://user-images.githubusercontent.com/74038190/212749447-bfb7e725-6987-49d9-ae85-2015e3e7cc41.gif" />

```elixir
defmodule DevAnalyst do
  defstruct name: "Rayelisson Lima",
            role: "Dev. Backend",
            languages: ["Elixir", "Ruby", "Go"],
            frameworks: %{
              "Elixir" => ["Phoenix"],
              "Ruby" => ["Rails"],
              "Go" => ["Gin"]
            },
            databases: ["PostgreSQL", "MongoDB"],
            dev_ops_tools: ["AWS", "Docker", "Git", "GitHub"],
            methodologies: ["Scrum", "Kanban"]

  def introduce(%__MODULE__{} = dev_analyst) do
    IO.puts("Hi, I'm #{dev_analyst.name}, a #{dev_analyst.role}.")
    IO.puts("Here's what I specialize in:")
    IO.puts("Languages: #{Enum.join(dev_analyst.languages, ", ")}")

    IO.puts("Frameworks:")
    Enum.each(dev_analyst.frameworks, fn {lang, fwks} ->
      IO.puts("  #{lang}: #{Enum.join(fwks, ", ")}")
    end)

    IO.puts("Databases: #{Enum.join(dev_analyst.databases, ", ")}")
    IO.puts("DevOps Tools: #{Enum.join(dev_analyst.dev_ops_tools, ", ")}")
    IO.puts("Methodologies: #{Enum.join(dev_analyst.methodologies, ", ")}")
  end
end

# Instanciar e exibir a introdução
dev_analyst = %DevAnalyst{}
DevAnalyst.introduce(dev_analyst)


```

## 📚 Minha Trajetória de Aprendizado
### 🧪 Desenvolvimento Backend

<!-- START OF PROFILE STACK, DO NOT REMOVE -->
| 💻 **Technology** | 🚀 **Projects** |
| - | - |
| [![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=for-the-badge&logo=elixir&logoColor=white)](https://www.gnu.org/)| [![webryseg](https://img.shields.io/static/v1?label=&message=webryseg&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/rayelissonl/webryseg) [![banana_bankk](https://img.shields.io/static/v1?label=&message=banana_bankk&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/notion-interactive-brokers) [![notion-habit-tracker](https://img.shields.io/static/v1?label=&message=notion-habit-tracker&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/notion-habit-tracker) [![hackclubnmit/certificate-generator](https://img.shields.io/static/v1?label=&message=certificate-generator&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/hackclubnmit/certificate-generator) [![todo-cli](https://img.shields.io/static/v1?label=&message=todo-cli&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/todo-cli) [![option-chain-notifier](https://img.shields.io/static/v1?label=&message=option-chain-notifier&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/option-chain-notifier) |
| [![Ruby on Rails](https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)](https://www.gnu.org/) | [![projray_airbnb](https://img.shields.io/static/v1?label=&message=projray_airbnb&color=000605&logo=gitlab&logoColor=FFFFFF&labelColor=000605)](https://gitlab.com/rayelisson/projray_airbnb) |
| [![Golang](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://nodejs.org/en/) | [![speaking-geo-assistant-backend](https://img.shields.io/static/v1?label=&message=speaking-geo-assistant-backend&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/speaking-geo-assistant-backend) [![dietary-care](https://img.shields.io/static/v1?label=&message=dietary-care&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/dietary-care) |
| [![FastAPI](https://img.shields.io/static/v1?label=&message=FastAPI&color=009688&logo=FastAPI&logoColor=FFFFFF)](https://fastapi.tiangolo.com/) | [![fast_ray_ap](https://img.shields.io/static/v1?label=&message=fast_ray_ap&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/rayelissonl/fast_ray_ap) [![strategical-trading](https://img.shields.io/static/v1?label=&message=strategical-trading%20(WIP)&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/strategical-trading) |
| [![Flask](https://img.shields.io/static/v1?label=&message=Flask&color=000000&logo=Flask&logoColor=FFFFFF)](https://flask.palletsprojects.com/en/2.1.x/) | [![bitgrit-personality-api](https://img.shields.io/static/v1?label=&message=bitgrit-personality-api&color=000605&logo=gitlab&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/bitgrit-personality-api) [![tradingview-discord-middleware](https://img.shields.io/static/v1?label=&message=tradingview-discord-middleware&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/tradingview-discord-middleware) |
| [![Django](https://img.shields.io/static/v1?label=&message=Django&color=092E20&logo=Django&logoColor=FFFFFF)](https://www.djangoproject.com/) | [![todo-list-battle](https://img.shields.io/static/v1?label=&message=todo-list-battle%20(WIP)&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/todo-list-battle) |
|  [![Python](https://img.shields.io/static/v1?label=&message=Python&color=3776AB&logo=Python&logoColor=FFFFFF)](https://www.python.org/) | [![projray_airbnb](https://img.shields.io/static/v1?label=&message=projray_airbnb&color=000605&logo=gitlab&logoColor=FFFFFF&labelColor=000605)](https://gitlab.com/rayelisson/projray_airbnb) |
| [![Nest.js](https://img.shields.io/badge/-NestJs-ea2845?style=flat-square&logo=nestjs&logoColor=white)](https://nodejs.org/en/) | [![full_stack_nestjs_react_amzry](https://img.shields.io/static/v1?label=&message=full_stack_nestjs_react_amzry&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/Rayelisson/full_stack_nestjs_react_amzry) [![dietary-care](https://img.shields.io/static/v1?label=&message=dietary-care&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/dietary-care) |
| [![JavaScript](https://img.shields.io/static/v1?label=&message=JavaScript&color=F7DF1E&logo=JavaScript&logoColor=FFFFFF)](https://javascript.info/) | [![wwf](https://img.shields.io/static/v1?label=&message=www&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/www) [![anuragsingh.dev](https://img.shields.io/static/v1?label=&message=anuragsingh.dev&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/anuragsingh.dev) [![unshorts](https://img.shields.io/static/v1?label=&message=unshorts&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/unshorts) |
| [![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.gnu.org/) | [![dotfiles-public](https://img.shields.io/static/v1?label=&message=dotfiles-public&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/dotfiles-public) |
| [![Node.js](https://img.shields.io/static/v1?label=&message=Node.js&color=339933&logo=Node.js&logoColor=FFFFFF)](https://nodejs.org/en/) | [![speaking-geo-assistant-backend](https://img.shields.io/static/v1?label=&message=speaking-geo-assistant-backend&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/speaking-geo-assistant-backend) [![dietary-care](https://img.shields.io/static/v1?label=&message=dietary-care&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/dietary-care) |
| [![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://www.gnu.org/) | [![dotfiles-public](https://img.shields.io/static/v1?label=&message=dotfiles-public&color=000605&logo=docker&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/dotfiles-public) [![dotfiles-public](https://img.shields.io/static/v1?label=&message=dotfiles-public&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/dotfiles-public) |
| [![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white) ](https://www.gnu.org/) | [![dotfiles-public](https://img.shields.io/static/v1?label=&message=dotfiles-public&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/dotfiles-public) |
| [![Problem solving](https://img.shields.io/static/v1?label=&message=Problem%20solving&color=FFA116&logo=LeetCode&logoColor=FFFFFF)](https://hackattic.com/u/ashleymavericks) | [![leetcoding](https://img.shields.io/static/v1?label=&message=leetcoding&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/leetcoding) [![hackerrank](https://img.shields.io/static/v1?label=&message=hackerrank&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/hackerrank) [![hackattic](https://img.shields.io/static/v1?label=&message=hackattic&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/hackattic) [![kata-log](https://img.shields.io/static/v1?label=&message=kata-log&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/kata-log) [![sadservers](https://img.shields.io/static/v1?label=&message=sadservers&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/sadservers) [![code.golf](https://img.shields.io/static/v1?label=&message=code.golf&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/code.golf) [![system-design](https://img.shields.io/static/v1?label=&message=system-design&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/system-design) |
<!-- END OF PROFILE STACK, DO NOT REMOVE -->
<hr>



<!-- START OF PROFILE STACK, DO NOT REMOVE -->
<!--

| [![Ruby on Rails](https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)](https://www.gnu.org/) | [![projray_airbnb](https://img.shields.io/static/v1?label=&message=projray_airbnb&color=000605&logo=gitlab&logoColor=FFFFFF&labelColor=000605)](https://gitlab.com/rayelisson/projray_airbnb) |
| [![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=for-the-badge&logo=elixir&logoColor=white)](https://www.gnu.org/) | [![projray_airbnb](https://img.shields.io/static/v1?label=&message=projray_airbnb&color=000605&logo=gitlab&logoColor=FFFFFF&labelColor=000605)](https://gitlab.com/rayelisson/projray_airbnb) |
| [![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.gnu.org/) | [![projray_airbnb](https://img.shields.io/static/v1?label=&message=projray_airbnb&color=000605&logo=gitlab&logoColor=FFFFFF&labelColor=000605)](https://gitlab.com/rayelisson/projray_airbnb) |
| [![Ruby on Rails](https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)](https://www.gnu.org/) | [![projray_airbnb](https://img.shields.io/static/v1?label=&message=projray_airbnb&color=000605&logo=gitlab&logoColor=FFFFFF&labelColor=000605)](https://gitlab.com/rayelisson/projray_airbnb) |
### 🧪 Data Science / ML
| 💻 **Technology** | 🚀 **Projects** |
| - | - |
| [![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://www.gnu.org/) | [![dotfiles-public](https://img.shields.io/static/v1?label=&message=dotfiles-public&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/dotfiles-public) |
| [![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ](https://javascript.info/) | [![www](https://img.shields.io/static/v1?label=&message=dotfiles-public&color=000605&logo=kaggle&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/dotfiles-public) [![anuragsingh.dev](https://img.shields.io/static/v1?label=&message=anuragsingh.dev&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/anuragsingh.dev) [![unshorts](https://img.shields.io/static/v1?label=&message=unshorts&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/unshorts) |
| [![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://nodejs.org/en/) | [![speaking-geo-assistant-backend](https://img.shields.io/static/v1?label=&message=speaking-geo-assistant-backend&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/speaking-geo-assistant-backend) [![dietary-care](https://img.shields.io/static/v1?label=&message=dietary-care&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/dietary-care) |
| [![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://nodejs.org/en/) | [![speaking-geo-assistant-backend](https://img.shields.io/static/v1?label=&message=speaking-geo-assistant-backend&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/speaking-geo-assistant-backend) [![dietary-care](https://img.shields.io/static/v1?label=&message=dietary-care&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/dietary-care) |
| [![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)  ](https://hackattic.com/u/ashleymavericks) | [![leetcoding](https://img.shields.io/static/v1?label=&message=leetcoding&color=000605&logo=powerbi&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/leetcoding) [![hackerrank](https://img.shields.io/static/v1?label=&message=hackerrank&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/hackerrank) [![hackattic](https://img.shields.io/static/v1?label=&message=hackattic&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/hackattic) [![kata-log](https://img.shields.io/static/v1?label=&message=kata-log&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/kata-log) [![sadservers](https://img.shields.io/static/v1?label=&message=sadservers&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/sadservers) [![code.golf](https://img.shields.io/static/v1?label=&message=code.golf&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/code.golf) [![system-design](https://img.shields.io/static/v1?label=&message=system-design&color=000605&logo=github&logoColor=FFFFFF&labelColor=000605)](https://github.com/ashleymavericks/system-design) |
| [![Ruby on Rails](https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)](https://www.gnu.org/) | [![projray_airbnb](https://img.shields.io/static/v1?label=&message=projray_airbnb&color=000605&logo=gitlab&logoColor=FFFFFF&labelColor=000605)](https://gitlab.com/rayelisson/projray_airbnb) |
| [![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=for-the-badge&logo=elixir&logoColor=white)](https://www.gnu.org/) | [![projray_airbnb](https://img.shields.io/static/v1?label=&message=projray_airbnb&color=000605&logo=gitlab&logoColor=FFFFFF&labelColor=000605)](https://gitlab.com/rayelisson/projray_airbnb) |
-->

<hr>
<h2 >⚡ Stats ⚡</h2>
<br>
 <img  height="130em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rayelissonl&theme=dark&layout=compact" />
 <img  height="130em" src="https://github-readme-stats.vercel.app/api?username=rayelissonl&theme=dark&show_icons=true" />
<hr>
    
     

#### Social networks!

<div  style="display: inline-block"> 

 <a href="https://www.linkedin.com/in/rayelisson-lima-74085162/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
      <a href="https://www.kaggle.com/rayelissonlima" target="_blank"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" target="_blank"></a>
      
</div>
