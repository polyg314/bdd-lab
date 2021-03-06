#BDD Lab

##Starting Point
* You are provided with a new rails app containing a `welcome#index` & `welcome#about`
* The TDD portion, aka the controller & routing specs, have already been written for you

##Objectives

Impliment BDD with two tests:

1) Assert that the `welcome/index` view displays a "Hello World" message in an `<h1>`

2) Assert that when we click an `<a>` tag containing the message `see about` on `welcome#index`, we are redirected to `welcome#about` and on the `welcome/about` view we see a `<ul>` with the class `.about` listing `<li>`s, each containing an interesting fact about yourself.

##Process

* Add `Capybara`
* Create a folder in `/spec` called `features`
* In `spec/features` create a file named `welcome_feature_spec.rb` containing your tests
* Run the tests ensuring they initially fail
* Finally, write the code to make them pass!
