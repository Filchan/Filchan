```js
class Base {
  constructor() {
    return {
      who_i_am: `2.5 yılı aşkın bir süredir JavaScript ile Discord üzerinde bot geliştiriyorum. 
Kendi kendimi geliştirebiliyor ve yeni şeyleri kolayca öğrenebiliyorum. 
Günümün yarısını uyumak,  geri kalan zamanın çoğunu Discord ile ilgilenip videolar izlemekle geçiriyorum. 
Sosyal bir hayatım olmadığından çoğu zaman evdeyim.`,
      name: 'Gökhan Can',
      weight: 90,
      height: 173,
      hobies: ['🍷', '🎮', '💻'],
      using: {
        languages: [
          { name: 'JavaScript', percent: 80, for: '2-3 years' }, 
          { name: 'HTML5', percent: 20, for: '1-6 Months' }, 
          { name: 'CSS', percent: 10, for: '1-6 Months' }
        ],
        librarys: ['Discord.js', 'Eris']
      },
      contacts: [
        { name: 'Discord', url: 'https://discord.com/users/613700645173592086' },
        { name: 'Instagram', url: 'https://instagram.com/thiskyhan' }
      ],
      project: {
        Blindcord: { 
          description: 'Blincord, kullanıcılar arası anonim sohbeti sağlayan Discord sunucusudur.',
          url: 'https://discord.com/invite/blindcord',
          status: 'Beta'
        },
        Raven: {
          description: 'Gelişmeyi hedefleyen olağanüstü bir Topluluktur. İyi arkadaşlıklar kurabileceğin sıcak bir ortamdır.',
          url: null,
          status: 'Closed for now'
        },
        gets_from_username: {
          description: 'NPM Package',
          url: 'https://github.com/chimpdev/gets-from-username',
          status: 'Online'
        }
      },
    };
  };
};

new Base();
```
