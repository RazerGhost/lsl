`# Laravel Jetstream Livewire Social Login Integration

This guide will walk you through the steps to integrate GitHub and Google social logins into your Laravel Jetstream Livewire application. We will be using Laravel Socialite package for this purpose.

## Prerequisites

Before proceeding with the integration, please ensure that you have the following prerequisites installed:

- PHP (>= 7.3)
- Composer
- Laravel (>= 8.x)
- Laravel Jetstream (>= 2.x)
- Laravel Livewire (>= 2.x)

## Step 1: Install Laravel Socialite

First, let's install the Laravel Socialite package using Composer. Open your terminal and navigate to your Laravel project directory. Run the following command:

```shell
composer require laravel/socialite
```

Step 2: Configure GitHub Social Login
-------------------------------------

1.  Follow the guide available at [Laravel 9 Socialite Login with GitHub](https://www.itsolutionstuff.com/post/laravel-9-socialite-login-with-github-account-exampleexample.html) to set up GitHub social login.
2.  The guide will provide step-by-step instructions to install the required dependencies, configure routes, views, and handle the authentication process.
3.  Make sure to follow all the instructions and update the necessary files as mentioned in the guide.

Step 3: Configure Google Social Login
-------------------------------------

1.  Refer to the guide provided by [PositronX](https://www.positronx.io/laravel-9-socialite-login-with-google-example-tutorial/) to integrate Google social login into your Laravel application.
2.  This guide will walk you through the process of installing the required dependencies, setting up Google OAuth credentials, and updating the relevant files for authentication.
3.  Follow the guide carefully and make the necessary changes in your application as instructed.

Step 4: Test the Social Logins
------------------------------

After completing the configuration steps, you can now test the GitHub and Google social logins in your Laravel Jetstream Livewire application.

-   Start your Laravel development server using the `php artisan serve` command.
-   Visit your application in the browser and navigate to the login page.
-   You should see options to log in with GitHub and Google.
-   Click on the respective social login button, and you will be redirected to the corresponding social provider's login page.
-   After successfully logging in, you will be redirected back to your application and logged in with the social provider's credentials.

Congratulations! You have successfully integrated both GitHub and Google social logins into your Laravel Jetstream Livewire application using Laravel Socialite.

Feel free to explore and customize the login functionality according to your application's requirements.

Additional Resources
--------------------

-   Laravel Socialite documentation: [Laravel Socialite](https://laravel.com/docs/socialite)
-   Laravel Jetstream documentation: [Laravel Jetstream](https://jetstream.laravel.com)
-   Laravel Livewire documentation: [Laravel Livewire](https://laravel-livewire.com)
