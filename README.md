#### oi 

🦹‍♂️ 🇲🇽

```ruby
module Presenter
  class EngineerPresenter
    def self.present(engineer)
      return if engineer.bland?

      engineer.values
    end
  end  
end

# Who I am
pro_bio = 'Senior Software Engineer | Project Manager | Lead developer | 13 years of exp | Mexican'

me = { name: 'Vic Carrasco', aka: '1ronin', power_level: 1.step.size, bio: pro_bio, skills: ['Ruby / Rails', 'SQL', 'GIT', 'Agile', 'Project Management'], hobbies: ['Coding', 'Boxing', 'Martial Arts', 'Cycling', 'Photography'] }

viccarrasco = Struct.new(*me.keys) do
  def bland?
    power_level <= 999_999_999
  end
end.new(*me.values)

Presenter::EngineerPresenter.present(viccarrasco)
```

- I do code; mostly specialized in ruby/rails services
- I believe in clean code & clean architecture

<!--
**viccarrasco/viccarrasco** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### Reach out
- [Let's connect](https://www.linkedin.com/in/viccarrasco/)

![GitHub stats](https://github-readme-stats.vercel.app/api?username=viccarrasco&show_icons=true&theme=calm)
