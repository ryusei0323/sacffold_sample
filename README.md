# scaffoldの使い方
- rails generate scaffold モデル名 カラム名1:データ型1 ……
- (rails g scaffold モデル名 カラム名1:データ型1 ……)

scaffoldとはRuby on Rails上で、MVCフレームワークのテンプレートとなるファイルを作成してくれるジェネレーターです。scaffoldという言葉自体の意味は「土台」を意味しています

## 生成されるファイル
- db/migrate/YYYYMMDDHHMMSS_create_モデル名.rb
- app/model/モデル名.rb
- app/views/モデル名/index.html.erb
- app/views/モデル名/edit.html.erb
-  app/views/モデル名/show.html.erb
- app/views/モデル名/new.html.erb
- app/views/モデル名/_form.html.erb
- test/controllers/モデル名_controller_test.rb
- app/helpers/モデル名_helper.rb
- test/helpers/モデル名_helper_test.rb
- app/views/モデル名/index.json.jbuilder
-  app/views/モデル名/show.json.jbuilder
- app/assets/javascripts/モデル名.js.coffee
- app/assets/stylesheets/モデル名.css.scss
- app/assets/stylesheets/scaffolds.css.scss