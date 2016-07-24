#[Go Digital with Us](http://www.godigitalwith.us/)
![ruby version](https://img.shields.io/badge/ruby-2.3.1-brightgreen.svg)

<center>
  ![](https://www.whitehouse.gov/profiles/forall/modules/custom/gov_whitehouse_www/images/icons/wh_logo_seal.png "White House")
</center>

#####*A web platform to help close the Digital Divide in collaboration with the White House*
---

### Table of Contents
* [What is Go Digital with Us?](#what-is-go-digital-with-us?)
* [How to contribute](#how-to-contribute)
* [Getting started](#getting-started)

---

### What is Go Digital with Us?
The Obama Administration announced the [ConnectALL Initiative](http://make.sc/whitehouse) in March 2016 to give all Americans access to broadband connectivity. In order to do so, the administration called on the tech community to help the United States to move more of its population on to the Internt. A team of students at [Make School](https://www.makeschool.com/founding-class) conducted weeks of user research and designed GDwU as an open-sourced curated online repository of Internet/computer skills tutorials as a mobile-friendly responsive web-app.

A basic digital literacy suite is shipped with the app of Computer Basics and Internet Basics as a tool for those just getting started with new technologies. Content is contritubed to by the nationwide community of "tech helpers". Our tech helpers include tech labs, librarians, volunteers and anyone who can provide tutorials to help our community become better connected throughout our nation.

### How to contribute
There are several ways to contribute to the project!

* **Contribute content**: In order to be successful, we need all of you to provide content to help those understand how to connect using the Internet. Things that seem basic and intuitive to those that have grown up with technology can seem daunting to many who have never used it. Spend 30 minutes creating a tutorial and submit it for review! It can be something a simple as creating an email account with yur favorite email service!

* **Create issues**: Found a bug? Have a suggestions? Please open an [issue](https://github.com/cmaher92/ConnectAll/issues) so we can take a look!

* **Contribute to our code**: Found a fix for a bug? Want to add a feature? Please take a look at our contributing guidelines and create a [pull request](https://github.com/cmaher92/ConnectAll/pulls) and we'll take a look!

* **Get involved**: If you'd like to get more involved, please feel free to contact us at `godigitalwithus@gmail.com`.

### Getting started

1. Clone the project
```
git clone https://github.com/cmaher92/ConnectAll.git
```
2. Install Ruby: If you already have Ruby and need to update to 2.3.1, skip to step 3.

    - Install Hombrew: If you have Homebrew, skip to next step.
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
    - Update Homebrew
```
    - brew update
```
    - Install Ruby
```
brew install ruby
```

3. Update Ruby

    - Update Homebrew
```
brew update
```
    - Update `ruby-build`
```
brew upgrade ruby-build
```
    - Install 2.3.1
```
rbenv install 2.3.1
```

4. Install bundler
```
gem install bundler
```

5. Install gems
```
bundle install
```
6. Run migrations
```
bin/rake db:migrate RAILS_ENV=development
```

7. Run the server
```
rails s
```

8. Go to localhost:3000
```
http://localhost:3000/
```