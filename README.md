<h2 align="center"> ALEXANDRA TRIVIÑO VASQUEZ </h2>

``` javascript
class softwareEngineer {
  constructor(name, title, skills, contact) {
    this.name = name;
    this.title = title;
    this.skills = skills;
    this.contact = contact;
  }

  introduce() {
    console.log(`Hola, mi nombre es ${this.name} y soy ${this.title}.`);
    this.displaySkills();
    this.displayContact();
  }

  displaySkills() {
    console.log('Estas son mis habilidades:');
    this.skills.forEach( skill => console.log(`- ${skill}`));
  }

  displayContact() {
    console.log('Puedes ponerte en contacto conmingo en las siguientes redes:');
    console.log(`Email: ${this.contact.email}`);
    console.log(`Linkedin: ${this.contact.linkedin}`);
    console.log(`Github: ${this.contact.github}`);
    console.log(`Instagram: ${this.contact.instagram}`);
  }
}

const miPerfil = softwareEngineer(
  'Alexandra Triviño Vasquez',
  'Software Engineer',
  [
    'HTML',
    'CSS',
    'SaSS',
    'Javascript',
    'React',
    'Jest',
    'Gherkin',
    'Ruby',
    'Rails',
    'Python',
    'Cucumber',
    'Node Js',
    'Boostrap',
    'Tailwind CSS',
    'Express',
    'MySQL',
    'POstgreSQL',
    'Git',
    'GitHub',
    'Datadog',
    'New Relic',
    'Postman'
  ],
  {
    email: 'alexandratrivino2@gmail.com',
    linkedin: 'alexandra-trivino',
    github: 'atrivinov',
    instagram: 'atrivinov'
  }
);

miPerfil.introduce();
```
