```bash
ruby bin/rails server
ruby bin/rails generate controller Articles index --skip-routes
ruby bin/rails generate model Article title:string body:text
ruby bin/rails db:migrate
ruby bin/rails console
article = Article.new(title: "Hello Rails", body: "I am on Rails!")
article.save
article
Article.find(1)
Article.all

ruby bin/rails routes 

ruby bin/rails generate model Comment commenter:string body:text article:references
ruby bin/rails db:migrate
ruby bin/rails generate controller Comments
```