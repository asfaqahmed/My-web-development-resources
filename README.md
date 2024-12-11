# My-web-deveopment-resources

# 140 Python Projects with Source Code
https://medium.datadriveninvestor.com/140-python-projects-with-source-code-fa12c9e2aeac

# another projects download website - checked this website we can download code easily
https://codeastro.com/

## python project download website
https://projectworlds.in/python-projects-with-source-code/bank-management-system-project-in-python/

## django web application list
https://www.ordinarycoders.com/blog/article/django-projects-github

##itsourcecode.com
https://itsourcecode.com/sdm_downloads/portfolio-management-system-project-in-django-with-source-code/

## django affiate marketing web application code link 
https://github.com/goldminer1030/django-affiliate-marketing

## frontEndMentor & codepen website for exploring designs

## dash for analytica and charts showcase
https://plotly.com/dash/

## for security in djnago
https://www.django-cms.org/en/blog/2022/02/22/security-enhancements-for-django-cms/

## django Jobs : search  Django Job Portalin Django documents


#Laravel projects cloning in github
## clone the repo
git clone https://github.com/devzakir/laravel-complete-blog-development.git laravel-blog

## install composer dependency
composer install

when you get conflict in composer packages try this command
##composer install --ignore-platform-reqs

## create a environment file
cp .env.example .env

## set the Application key
php artisan key:generate

## comment database query in AppServiceProvider.php like this
// $categories = Category::take(5)->get();
// View::share('categories', $categories);

// $setting = Setting::first();
// View::share('setting', $setting);

## setup the database credentials and migrate database with seeders
php artisan migrate --seed

## enable the database query code in AppServiceProvider.php like this
$categories = Category::take(5)->get();
View::share('categories', $categories);

$setting = Setting::first();
View::share('setting', $setting);
