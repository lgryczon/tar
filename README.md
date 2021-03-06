## Testowanie aplikacji w Ruby, 2015/16

----
![refactoring](images/refactoring.jpg)
----

1. Powtórka z języka Ruby.
   - [Learn X in Y minutes][5], where X=Ruby.
   - [Learn X in Ruby], where X=Array,Hash (laboratorium, git)
2. Ogólnie o testowaniu, dostępne narzędzia i technologie:<br>
   - Edytor i Testowanie
   - [Learn X in Y minutes], where X=Rspec,Capybara,Factory Girl
3. Wprowadzenie do RSpec.
4. Testy jednostkowe.
5. Testy integracyjne.
6. Refaktoryzacja kodu.
7. Pokrycie kodu testami.
   - [simplecov][8]
8. Doubles, mocks i stubs.
9. Praca z *Legacy Code* (zastanym kodem, kodem niepokrytym testami).

### RSpec

> There are only two types of theories [programms]:<br>
> 1. Theories that are known to be wrong, as they were tested
> and adequately rejected.<br>
> 2. Theories that have not yet been known to be wrong,
> not falsified yet, but are exposed to be wrong.<br>
> – *K. Popper*<br>
> Why is the theory [program] **never right**?


1. David Chelimsky, Dave Astels, Zach Dennis, Aslak Hellesøy, Bryan Helmkamp, Dan North.
   [The RSpec Book: Behaviour-Driven Development with RSpec, Cucumber, and Friends][3].
2. [Better Specs](http://betterspecs.org/).
3. Dokumentacja [RSpec](http://rspec.info/):
  - [rspec-core](https://github.com/rspec/rspec-core)
  - [rspec-expectations](https://github.com/rspec/rspec-expectations)
  - [rspec-mocks](https://github.com/rspec/rspec-mocks)

### Ruby

1. [Ruby Tutorial][4].
2. [Ruby Koans](http://rubykoans.com/) – Learn Ruby with the Neo Ruby Koans.
3. Jay Fields, Shane Harvie, Martin Fowler with Kent Beck.
   [Refactoring](http://books.google.pl/books/about/Refactoring.html?id=6jyOUrJBJHAC) – Ruby edition.
4. [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide) – a community-driven Ruby coding style guide

### Git

* Scott Chacon, Ben Straub. [Pro Git](https://git-scm.com/book/en/v2)
  - [6.1 GitHub – Account Setup and Configuration](https://git-scm.com/book/en/v2/GitHub-Account-Setup-and-Configuration)
  - [6.2 GitHub - Contributing to a Project](https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project)

### Continuous Integration and Deployment

1. [Codeship](https://www.codeship.io/).
1. [Travis](https://travis-ci.org/) – niestety usługa płatna dla repozytoriów prywatnych.

----

* [Codility](https://codility.com/) – we test coders


[5]: http://learnxinyminutes.com/docs/ruby/
[1]: https://github.com/elizabrock/NSS-Syllabus-Spring-2013
[2]: http://rvm.io/rvm
[3]: http://pragprog.com/book/achbd/the-rspec-book
[4]: http://www.tutorialspoint.com/ruby/
[6]: http://tryruby.org/levels/1/challenges/0
[7]: https://www.codeschool.com/courses/testing-with-rspec
[8]: https://github.com/colszowka/simplecov
