# პროექტის აწყობა GULP 4-ის გამოყენებით
მიყევით ინსტრუქციას, და მარტივად შეძლებთ თქვენი პროექტისთვის GULP 4-ის ნაკრების აწყობას და კოდის წერას:
- HTML, PUG
- CSS, SCSS, SASS, LESS, STYLUS
- Java Script, Type Script, Coffee Script

## ნაკრების ფუნქციონალი
- PUG-ის კომპილაცია
- HTML-ის მინიფიკაცია
- LESS, SASS, STYLUS კომპილაცია
- CSS-ის მინიფიკაცია
- CSS პრეფიქსების ავტომატური დამატება
- Type Script და Coffee Script ენების ტრანსპილაცია
- ECMAScript 2015 კოდის გარდაქმნა + უკუგარდაქმნა JavaScript თავსებად კოდათ Babel-ს მეშვეობით
- JavaScript-ის მინიფიკაცია
- რამოდენიმე JavaScript ფაილის გაერთიანება ერთ ფაილად
- გამოსახულების შეკუმშვა
- ახალი, ჯერ კიდევ შეუკუმშავი გამოსახულებების თვალთვალი
- ფაილებში ცვლილებების თვალთავლი და განმეორებითი დამუშავების ავტომატური გაშვება
- sourcemaps-ის გენერაცია
- ფაილების ზომის ასახვა ტერმინალში
- ლოკალური სერვერი, ფაილების ცვლილებისას გვერდის ავტომატური განახლებთ

## Input
|| HTML | Styles | Scripts | Images |
|:---|:------:|:-----:|:----:|:-----:|
| **კატალოგი** | src/ | src/styles/ | src/scripts/ | src/img/ |
| **გაფართოება** | .html, .pug | .css, .sass, .scss, .less, .styl | .js, .ts, .coffee | .jpg, .png, .gif |

## Output
|| HTML | CSS | JavaScript | Images |
|:---|:------:|:-----:|:----:|:-----:|
| **გზა** | dist/ | dist/css/style.min.css | dist/js/main.min.js | dist/img/ |

## ნაკრების გაშვება:  
1. გადაიწერეთ პროექტის ყველა ფაილი  
2. ტერმინალში გადადით პროქეტის კატალოგში 
3. შეასრულეთ: npm i (node.js წინასწარ უნდა იყოს დაინსტალირებული თქვენს მაქანაზე)  
4. შექმენით კატალოგები და ფაილები
5. შეასრულეთ ბრძანება: gulp   
6. წერეთ კოდი და ისიამოვნეთ პროექტის ავტომატური აწყობით

## გამოყენებული NPM პაკეტები
[gulp](https://www.npmjs.com/package/gulp) Gulp შემკრები  
[gulp-htmlmin](https://www.npmjs.com/package/gulp-htmlmin) HTML ფაილების მინიფიკატორი  
[gulp-pug](https://www.npmjs.com/package/gulp-pug) Pug  
[gulp-less](https://www.npmjs.com/package/gulp-less) Less ფაილების კომპილაცია  
[gulp-stylus](https://www.npmjs.com/package/gulp-stylus) Styl ფაილების კომპილაცია  
[sass](https://www.npmjs.com/package/sass) Sass კომპილატორი
[gulp-sass](https://www.npmjs.com/package/gulp-sass) Sass და Scss ფაილების კომპილაცია  
[gulp-uglify](https://www.npmjs.com/package/gulp-uglify) Java Script კოდის შეკუმშვა დ აოპტიმიზაცია  
[gulp-coffee](https://www.npmjs.com/package/gulp-coffee) გარდაქმნის Coffee Script-ს Java Script-ში  
[gulp-typescript](https://www.npmjs.com/package/gulp-typescript) გარდაქმნის Type Script-ს Java Script-ში 
[typescript](https://www.npmjs.com/package/typescript) Type Script  
[gulp-babel](https://www.npmjs.com/package/gulp-babel) გარდაქმნის Java Script-ს ძველ სტანდარტში  
[@babel/core](https://www.npmjs.com/package/@babel/core) Babel core
[@babel/preset-env](https://www.npmjs.com/package/@babel/preset-env) პრესეტი Babel-ის კომპილაციისთვის  
[gulp-clean-css](https://www.npmjs.com/package/gulp-clean-css) CSS ფაილების ოპტიმიზაცია და მინფიკაცია   
[del](https://www.npmjs.com/package/del) კატალოგების ფაილების წაშლა  
[gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps) კოდის სტრიქონების რუქა დეველოპერებისთვის   
[gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer) CSS-ში პრეფიქსების ავტომატური დამატება
[gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin) გამოსახულების შეკუმშვა   
[gulp-concat](https://www.npmjs.com/package/gulp-concat) რამოდენიმე ფაილეის გაერთიანება  
[gulp-newer](https://www.npmjs.com/package/gulp-newer) მხოლოდ ახალი ფაილების თვალთვალი  
[gulp-rename](https://www.npmjs.com/package/gulp-rename) ფაილების სახელების გადარქმევა    
[gulp-size](https://www.npmjs.com/package/gulp-size) ფაიელბის ზომების ტერმინალში ასახვა  
[browser-sync](https://browsersync.io/docs/gulp) საიტის ავტომატური აღდგენა ფაილებში ცვლილებეისას 
