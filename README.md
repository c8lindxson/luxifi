LUXIFI

Market place for renting designer brand items. Users can add items to be listed and request items they would like to rent. 

<img width="828" alt="luxifi- my closet page" src="https://github.com/c8lindxson/luxifi/assets/128205478/d79d9d02-e63f-460e-8d05-ab82676de8cc">
<img width="913" alt="luxifi- new in page" src="https://github.com/c8lindxson/luxifi/assets/128205478/b6f5c8dd-08de-45e5-8915-7f88ca68d0dc">
<br>
App home: (https://luxifi.herokuapp.com/)
   

## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping

## Acknowledgements
Thank you to Le Wagon Tokyo for the guidance and amazing learning experiences from this challenge.

## Team Members
- [Cai Dixon]
- Fumi Nozawa
- Anne Garvey
- Taylor Ellis

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License
