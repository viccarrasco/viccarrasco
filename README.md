## hello there :v: 

I'm Vic, a senior sde from 🇲🇽 living in 🇩🇪. With experience as team lead and agile project management. 

##### What I do now
![GIT](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white)

##### Using
![VS CODE](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![iTerm](https://img.shields.io/badge/iTerm2-000000?style=for-the-badge&logo=iterm2&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

##### Let's connect
[![Linked IN](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/viccarrasco/)

```ruby
module Presenter
  class EngineerPresenter
    def self.present(engineer)
      return if engineer.discard?

      engineer.values
    end
  end  
end

# Who I am
me = {
  name: 'Vic Carrasco',
  aka: '1ronin',
  bio: 'Senior Software Engineer | Project Manager | Lead developer | 13 years of exp | Mexican',
  power_level: 1.step.size,
  skills: ['Ruby / Rails', 'SQL', 'GIT', 'Agile', 'Project Management'],
  hobbies: ['Coding', 'Boxing', 'Martial Arts', 'Cycling', 'Photography']
}

viccarrasco = Struct.new(*me.keys) do
  def discard?
    power_level <= 999_999_999
  end
end.new(*me.values)

Presenter::EngineerPresenter.present(viccarrasco)
```

![GitHub stats](https://github-readme-stats.vercel.app/api?username=viccarrasco&show_icons=true&theme=calm)
