---
layout: post
title: Setup Laravel di Mac OS
date: 2018-11-15 08:21 +0700
categories: Laravel
author: Iman Sugirman
header:
    layout: hero        # Choose `hero` or `header`.
    navigation: fancy   # Optional: Set navigation to `fancy` to remove white navigation bar.
    class: bg-green     # Set a background colour class if not using a background image.
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

{% highlight php %}

<?php

namespace App\Http\Controllers;

use App\User;
use App\Forms\UserForms;
use App\Http\Controllers\Controller;

class UserController extends Controller
{

    public function index()
    {
        return view('user.profile', ['user' => User::findOrFail($id)]);
    }
}


{% endhighlight %}


#### Laravel
