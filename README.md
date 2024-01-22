<!-- model -->
rails g model Article title:string body:text
rails g model Comment commenter:string body:text article:references

<!-- migration -->
rails g migration AddStatusToArticles status:string
rails g migration AddStatusToComments status:string