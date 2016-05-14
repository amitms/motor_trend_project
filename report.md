



<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-3c1694fab1568340f2e75b26efa1f55d97c5153364a7357e9e1104c718ff1a2f.css" integrity="sha256-PBaU+rFWg0Dy51sm76H1XZfFFTNkpzV+nhEExxj/Gi8=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-3e95d73eb454e0099947df00d91ab0dbfc6b10be69dd5daf5de7aeb676580d20.css" integrity="sha256-PpXXPrRU4AmZR98A2Rqw2/xrEL5p3V2vXeeutnZYDSA=" media="all" rel="stylesheet" />
    
    
    
    

    <link as="script" href="https://assets-cdn.github.com/assets/frameworks-851de55546d87ad786f3efef3b5634f8f8a40d67fa6d44f854d9e99767e9c9a2.js" rel="preload" />
    
    <link as="script" href="https://assets-cdn.github.com/assets/github-9a6de3c5d3dd93cd9d6638a6d1bcc27eb7cbf9afdd082771ea900f9996597a24.js" rel="preload" />

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>Coursera-Regression-Models/report.md at master · amit/Coursera-Regression-Models</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/apple-touch-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/apple-touch-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon-180x180.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="https://avatars3.githubusercontent.com/u/1871047?v=3&amp;s=400" name="twitter:image:src" /><meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="amit/Coursera-Regression-Models" name="twitter:title" /><meta content="Coursera-Regression-Models - Repo for Coursera.com online course: Regression Models" name="twitter:description" />
      <meta content="https://avatars3.githubusercontent.com/u/1871047?v=3&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="amit/Coursera-Regression-Models" property="og:title" /><meta content="https://github.com/amit/Coursera-Regression-Models" property="og:url" /><meta content="Coursera-Regression-Models - Repo for Coursera.com online course: Regression Models" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTc3MTk3MDU6ODE1NDkxMWIxOGIxOTMxNDY2NzRkZDA5NmE0MGVjNDc6NzM3OTc2NGE0ZDJlOWI2NTEwODU2ODJlZTlkNGE5NDQ4Njg3ZjAyOTA0YjkyZTRkYzhiOTdjYTI0YTMzZTdiMQ==--60a168ce222a24935a226a59b11a0c8ff096543a">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="2D7598FD:2D07:EF6D38:57372A62" name="octolytics-dimension-request_id" /><meta content="17719705" name="octolytics-actor-id" /><meta content="amitms" name="octolytics-actor-login" /><meta content="07507176f04ad6aa35c9e48e07935c76d2eab5aa213f3a2a3eed4ca7fe4d17a5" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />



  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="amitms">

        <meta name="expected-hostname" content="github.com">
      <meta name="js-proxy-site-detection-payload" content="OTg4MmE4NjRhYzIxZDBiY2JiOTk3NjQxNjc0YjUxYmJjMDUwNDZkNzhhN2UzMjg2NzVlY2MwZDdjNmZiYzhkMXx7InJlbW90ZV9hZGRyZXNzIjoiNDUuMTE3LjE1Mi4yNTMiLCJyZXF1ZXN0X2lkIjoiMkQ3NTk4RkQ6MkQwNzpFRjZEMzg6NTczNzJBNjIiLCJ0aW1lc3RhbXAiOjE0NjMyMzMxMjJ9">


      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta content="4c050b4aaa53c8df46c85c43a0662326c5da8d7a" name="form-nonce" />

    <meta http-equiv="x-pjax-version" content="a4cb11b734331d95088899b1377fb05e">
    

      
  <meta name="description" content="Coursera-Regression-Models - Repo for Coursera.com online course: Regression Models">
  <meta name="go-import" content="github.com/amit/Coursera-Regression-Models git https://github.com/amit/Coursera-Regression-Models.git">

  <meta content="1871047" name="octolytics-dimension-user_id" /><meta content="amit" name="octolytics-dimension-user_login" /><meta content="22655652" name="octolytics-dimension-repository_id" /><meta content="amit/Coursera-Regression-Models" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="22655652" name="octolytics-dimension-repository_network_root_id" /><meta content="amit/Coursera-Regression-Models" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/amit/Coursera-Regression-Models/commits/master.atom" rel="alternate" title="Recent Commits to Coursera-Regression-Models:master" type="application/atom+xml">


      <link rel="canonical" href="https://github.com/amit/Coursera-Regression-Models/blob/master/motor_trend_project/report.md" data-pjax-transient>
  </head>


  <body class="logged-in   env-production windows vis-public page-blob">
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"></div>
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="28" version="1.1" viewBox="0 0 16 16" width="28"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59 0.4 0.07 0.55-0.17 0.55-0.38 0-0.19-0.01-0.82-0.01-1.49-2.01 0.37-2.53-0.49-2.69-0.94-0.09-0.23-0.48-0.94-0.82-1.13-0.28-0.15-0.68-0.52-0.01-0.53 0.63-0.01 1.08 0.58 1.23 0.82 0.72 1.21 1.87 0.87 2.33 0.66 0.07-0.52 0.28-0.87 0.51-1.07-1.78-0.2-3.64-0.89-3.64-3.95 0-0.87 0.31-1.59 0.82-2.15-0.08-0.2-0.36-1.02 0.08-2.12 0 0 0.67-0.21 2.2 0.82 0.64-0.18 1.32-0.27 2-0.27 0.68 0 1.36 0.09 2 0.27 1.53-1.04 2.2-0.82 2.2-0.82 0.44 1.1 0.16 1.92 0.08 2.12 0.51 0.56 0.82 1.27 0.82 2.15 0 3.07-1.87 3.75-3.65 3.95 0.29 0.25 0.54 0.73 0.54 1.48 0 1.07-0.01 1.93-0.01 2.2 0 0.21 0.15 0.46 0.55 0.38C13.71 14.53 16 11.53 16 8 16 3.58 12.42 0 8 0z"></path></svg>
</a>


        <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/amit/Coursera-Regression-Models/search" class="js-site-search-form" data-scoped-search-url="/amit/Coursera-Regression-Models/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
      <div class="header-search-scope">This repository</div>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        tabindex="1"
        autocapitalize="off">
    </label>
</form></div>


      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
    

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <svg aria-hidden="true" class="octicon octicon-plus left" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"></path></svg>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="amit/Coursera-Regression-Models">This repository</span>
  </div>
    <a class="dropdown-item" href="/amit/Coursera-Regression-Models/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/amitms"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@amitms" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/17719705?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu  dropdown-menu-sw">
        <div class=" dropdown-header header-nav-current-user css-truncate">
            Signed in as <strong class="css-truncate-target">amitms</strong>

        </div>


        <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/amitms" data-ga-click="Header, go to profile, text:your profile">
            Your profile
          </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
          <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
            Explore
          </a>
          <a class="dropdown-item" href="/integrations" data-ga-click="Header, go to integrations, text:integrations">
            Integrations
          </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>


          <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
            Settings
          </a>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="4c050b4aaa53c8df46c85c43a0662326c5da8d7a" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="jTT1jOaXUPDGXwjXGbo9ItLqtHqgIIZE/wugZ4nFq1r+LY0hvOmKq6ZVu+p5P85WXU2P7rcFY/us0wFMP9Yw5g==" /></div>
            <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
              Sign out
            </button>
</form>
      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>


      


    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main" class="main-content">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="4c050b4aaa53c8df46c85c43a0662326c5da8d7a" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="5JR3jlc1uN+XnWznXRHY6/vYYHMlntPNiFk8nok1p7/WjrbAb5+L3wEedJrdpH9ETTLbsFv64VYTslGro/p2FA==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="22655652" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/amit/Coursera-Regression-Models/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6c4.94 0 7.94-6 7.94-6S13 2 8.06 2z m-0.06 10c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4z m2-4c0 1.11-0.89 2-2 2s-2-0.89-2-2 0.89-2 2-2 2 0.89 2 2z"></path></svg>
              Watch
            </span>
          </a>
          <a class="social-count js-social-count" href="/amit/Coursera-Regression-Models/watchers">
            2
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6c4.94 0 7.94-6 7.94-6S13 2 8.06 2z m-0.06 10c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4z m2-4c0 1.11-0.89 2-2 2s-2-0.89-2-2 0.89-2 2-2 2 0.89 2 2z"></path></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6c4.94 0 7.94-6 7.94-6S13 2 8.06 2z m-0.06 10c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4z m2-4c0 1.11-0.89 2-2 2s-2-0.89-2-2 0.89-2 2-2 2 0.89 2 2z"></path></svg>
                      Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8 2.81v10.38c0 0.67-0.81 1-1.28 0.53L3 10H1c-0.55 0-1-0.45-1-1V7c0-0.55 0.45-1 1-1h2l3.72-3.72c0.47-0.47 1.28-0.14 1.28 0.53z m7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06 1.97 1.97-1.97 1.97 1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06-1.97-1.97 1.97-1.97z"></path></svg>
                      Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/amit/Coursera-Regression-Models/unstar" class="starred" data-form-nonce="4c050b4aaa53c8df46c85c43a0662326c5da8d7a" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="TyG2JysLGKGQTqP0YSYeVNpeRJLq9fx8r1sbXcNSD8Z8F6paC8nJwxvvghLKQHjMoiyr5UR1qySljlINMu0oJw==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar amit/Coursera-Regression-Models"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-0.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14l4.33-2.33 4.33 2.33L10.4 9.26 14 6z"></path></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/amit/Coursera-Regression-Models/stargazers">
          3
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/amit/Coursera-Regression-Models/star" class="unstarred" data-form-nonce="4c050b4aaa53c8df46c85c43a0662326c5da8d7a" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="rT3k1x8zuzQNmI9FszfKjv6SgWAzAMXQ9ILeDPHodflA6LHJlceaqng3zxbgcDk2QTT9OPArU77IY+jyRnabog==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star amit/Coursera-Regression-Models"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-0.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14l4.33-2.33 4.33 2.33L10.4 9.26 14 6z"></path></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/amit/Coursera-Regression-Models/stargazers">
          3
        </a>
</form>  </div>

  </li>

  <li>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/amit/Coursera-Regression-Models/fork" class="btn-with-count" data-form-nonce="4c050b4aaa53c8df46c85c43a0662326c5da8d7a" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="YUbzTdJtx3PrTM6dH5MYjzEcQX/dwdctuP2Gg8kUiNK9qypvz/79XYQPKgzepCdGbtOyTE+z2lPSGIwtV96LKg==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of amit/Coursera-Regression-Models to your account"
                aria-label="Fork your own copy of amit/Coursera-Regression-Models to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path d="M8 1c-1.11 0-2 0.89-2 2 0 0.73 0.41 1.38 1 1.72v1.28L5 8 3 6v-1.28c0.59-0.34 1-0.98 1-1.72 0-1.11-0.89-2-2-2S0 1.89 0 3c0 0.73 0.41 1.38 1 1.72v1.78l3 3v1.78c-0.59 0.34-1 0.98-1 1.72 0 1.11 0.89 2 2 2s2-0.89 2-2c0-0.73-0.41-1.38-1-1.72V9.5l3-3V4.72c0.59-0.34 1-0.98 1-1.72 0-1.11-0.89-2-2-2zM2 4.2c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z m3 10c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z m3-10c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z"></path></svg>
              Fork
            </button>
</form>
    <a href="/amit/Coursera-Regression-Models/network" class="social-count">
      124
    </a>
  </li>
</ul>

    <h1 class="entry-title public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M4 9h-1v-1h1v1z m0-3h-1v1h1v-1z m0-2h-1v1h1v-1z m0-2h-1v1h1v-1z m8-1v12c0 0.55-0.45 1-1 1H6v2l-1.5-1.5-1.5 1.5V14H1c-0.55 0-1-0.45-1-1V1C0 0.45 0.45 0 1 0h10c0.55 0 1 0.45 1 1z m-1 10H1v2h2v-1h3v1h5V11z m0-10H2v9h9V1z"></path></svg>
  <span class="author" itemprop="author"><a href="/amit" class="url fn" rel="author">amit</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/amit/Coursera-Regression-Models" data-pjax="#js-repo-pjax-container">Coursera-Regression-Models</a></strong>

</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/amit/Coursera-Regression-Models" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /amit/Coursera-Regression-Models" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M9.5 3l-1.5 1.5 3.5 3.5L8 11.5l1.5 1.5 4.5-5L9.5 3zM4.5 3L0 8l4.5 5 1.5-1.5L2.5 8l3.5-3.5L4.5 3z"></path></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/amit/Coursera-Regression-Models/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /amit/Coursera-Regression-Models/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7S10.14 13.7 7 13.7 1.3 11.14 1.3 8s2.56-5.7 5.7-5.7m0-1.3C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7S10.86 1 7 1z m1 3H6v5h2V4z m0 6H6v2h2V10z"></path></svg>
        <span itemprop="name">Issues</span>
        <span class="counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/amit/Coursera-Regression-Models/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /amit/Coursera-Regression-Models/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M11 11.28c0-1.73 0-6.28 0-6.28-0.03-0.78-0.34-1.47-0.94-2.06s-1.28-0.91-2.06-0.94c0 0-1.02 0-1 0V0L4 3l3 3V4h1c0.27 0.02 0.48 0.11 0.69 0.31s0.3 0.42 0.31 0.69v6.28c-0.59 0.34-1 0.98-1 1.72 0 1.11 0.89 2 2 2s2-0.89 2-2c0-0.73-0.41-1.38-1-1.72z m-1 2.92c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2zM4 3c0-1.11-0.89-2-2-2S0 1.89 0 3c0 0.73 0.41 1.38 1 1.72 0 1.55 0 5.56 0 6.56-0.59 0.34-1 0.98-1 1.72 0 1.11 0.89 2 2 2s2-0.89 2-2c0-0.73-0.41-1.38-1-1.72V4.72c0.59-0.34 1-0.98 1-1.72z m-0.8 10c0 0.66-0.55 1.2-1.2 1.2s-1.2-0.55-1.2-1.2 0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2z m-1.2-8.8c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z"></path></svg>
      <span itemprop="name">Pull requests</span>
      <span class="counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/amit/Coursera-Regression-Models/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /amit/Coursera-Regression-Models/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M2 5h4v1H2v-1z m0 3h4v-1H2v1z m0 2h4v-1H2v1z m11-5H9v1h4v-1z m0 2H9v1h4v-1z m0 2H9v1h4v-1z m2-6v9c0 0.55-0.45 1-1 1H8.5l-1 1-1-1H1c-0.55 0-1-0.45-1-1V3c0-0.55 0.45-1 1-1h5.5l1 1 1-1h5.5c0.55 0 1 0.45 1 1z m-8 0.5l-0.5-0.5H1v9h6V3.5z m7-0.5H8.5l-0.5 0.5v8.5h6V3z"></path></svg>
      Wiki
</a>

  <a href="/amit/Coursera-Regression-Models/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /amit/Coursera-Regression-Models/pulse">
    <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0V10h3.6L4.5 8.2l0.9 5.4L9 8.5l1.6 1.5H14V8H11.5z"></path></svg>
    Pulse
</a>
  <a href="/amit/Coursera-Regression-Models/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /amit/Coursera-Regression-Models/graphs">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M16 14v1H0V0h1v14h15z m-11-1H3V8h2v5z m4 0H7V3h2v10z m4 0H11V6h2v7z"></path></svg>
    Graphs
</a>

</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/amit/Coursera-Regression-Models/blob/cee856c81e56fee907e126f2b18f7be031bfc387/motor_trend_project/report.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:889fdeb2dee3c83a4dafcfe64b9b7ae2 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu branch-select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    title="master"
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/amit/Coursera-Regression-Models/blob/master/motor_trend_project/report.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/amit/Coursera-Regression-Models/find/master"
          class="js-pjax-capture-input btn btn-sm"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/amit/Coursera-Regression-Models"><span>Coursera-Regression-Models</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a href="/amit/Coursera-Regression-Models/tree/master/motor_trend_project"><span>motor_trend_project</span></a></span><span class="separator">/</span><strong class="final-path">report.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="right">
        <a class="commit-tease-sha" href="/amit/Coursera-Regression-Models/commit/72e0d2014a10890d2c97425bd8ccd6d8751878c3" data-pjax>
          72e0d20
        </a>
        <relative-time datetime="2015-01-25T17:04:49Z">Jan 25, 2015</relative-time>
      </span>
      <div>
        <img alt="@amit" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/1871047?v=3&amp;s=40" width="20" />
        <a href="/amit" class="user-mention" rel="author">amit</a>
          <a href="/amit/Coursera-Regression-Models/commit/72e0d2014a10890d2c97425bd8ccd6d8751878c3" class="message" data-pjax="true" title="Update report.md">Update report.md</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>1</strong>
         contributor
      </button>
      
    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@amit" height="24" src="https://avatars1.githubusercontent.com/u/1871047?v=3&amp;s=48" width="24" />
            <a href="/amit">amit</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/amit/Coursera-Regression-Models/raw/master/motor_trend_project/report.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/amit/Coursera-Regression-Models/blame/master/motor_trend_project/report.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/amit/Coursera-Regression-Models/commits/master/motor_trend_project/report.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="https://windows.github.com"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15 2H1c-0.55 0-1 0.45-1 1v9c0 0.55 0.45 1 1 1h5.34c-0.25 0.61-0.86 1.39-2.34 2h8c-1.48-0.61-2.09-1.39-2.34-2h5.34c0.55 0 1-0.45 1-1V3c0-0.55-0.45-1-1-1z m0 9H1V3h14v8z"></path></svg>
        </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/amit/Coursera-Regression-Models/edit/master/motor_trend_project/report.md" class="inline-form js-update-url-with-hash" data-form-nonce="4c050b4aaa53c8df46c85c43a0662326c5da8d7a" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="eMVo4bL7383iAHKuWdZhhZzNPYWi8EsYfyW81ydzg7vwM6igxmdEzJLZvt8Je9r1EYICGIJQwAoEdeLJyFFxmw==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M0 12v3h3l8-8-3-3L0 12z m3 2H1V12h1v1h1v1z m10.3-9.3l-1.3 1.3-3-3 1.3-1.3c0.39-0.39 1.02-0.39 1.41 0l1.59 1.59c0.39 0.39 0.39 1.02 0 1.41z"></path></svg>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/amit/Coursera-Regression-Models/delete/master/motor_trend_project/report.md" class="inline-form" data-form-nonce="4c050b4aaa53c8df46c85c43a0662326c5da8d7a" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="aXLvZ24ikG+6c6/ViZWPuTpO3qyaM6WfIfaEpo9zztNTJAq3kj3bKIyP/wLunM7qc/E5fNfLcKE9KLOpwTEo6A==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M10 2H8c0-0.55-0.45-1-1-1H4c-0.55 0-1 0.45-1 1H1c-0.55 0-1 0.45-1 1v1c0 0.55 0.45 1 1 1v9c0 0.55 0.45 1 1 1h7c0.55 0 1-0.45 1-1V5c0.55 0 1-0.45 1-1v-1c0-0.55-0.45-1-1-1z m-1 12H2V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9z m1-10H1v-1h9v1z"></path></svg>
          </button>
</form>  </div>

  <div class="file-info">
      189 lines (150 sloc)
      <span class="file-info-divider"></span>
    8.5 KB
  </div>
</div>

  
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><table data-table-type="yaml-metadata">
  <thead>
  <tr>
  <th>title</th>

  <th>author</th>

  <th>output</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>Regression Models Project - Motor Trend Data Analysis Report</div></td>

  <td><div>by amit (Sally) Zhang</div></td>

  <td><div><table>
  <thead>
  <tr>
  <th>pdf_document</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div><table>
  <thead>
  <tr>
  <th>fig_height</th>

  <th>fig_width</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>7</div></td>

  <td><div>7</div></td>
  </tr>
  </tbody>
</table></div></td>
  </tr>
  </tbody>
</table></div></td>
  </tr>
  </tbody>
</table>

<h2><a id="user-content-executive-summary" class="anchor" href="#executive-summary" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Executive Summary</h2>

<p>In this report, we will analyze <code>mtcars</code> data set and explore the relationship between a set of variables and miles per gallon (MPG). The data was extracted from the 1974 <em>Motor Trend</em> US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973–74 models). We use regression models and exploratory data analyses to mainly explore how <strong>automatic</strong> (am = 0) and <strong>manual</strong> (am = 1) transmissions features affect the <strong>MPG</strong> feature. The t-test shows that the performance difference between cars with automatic and manual transmission. And it is about 7 MPG more for cars with manual transmission than those with automatic transmission. Then, we fit several linear regression models and select the one with highest Adjusted R-squared value. So, given that weight and 1/4 mile time are held constant, manual transmitted cars are 14.079 + (-4.141)*weight more MPG (miles per gallon) on average better than automatic transmitted cars. Thus, cars that are lighter in weight with a manual transmission and cars that are heavier in weight with an automatic transmission will have higher MPG values.</p>

<h2><a id="user-content-exploratory-data-analysis" class="anchor" href="#exploratory-data-analysis" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Exploratory Data Analysis</h2>

<p>First, we load the data set <code>mtcars</code> and change some variables from <code>numeric</code> class to <code>factor</code> class.   </p>

<div class="highlight highlight-source-r"><pre>library(<span class="pl-smi">ggplot2</span>)
data(<span class="pl-smi">mtcars</span>)
<span class="pl-smi">mtcars</span>[<span class="pl-c1">1</span><span class="pl-k">:</span><span class="pl-c1">3</span>, ] <span class="pl-c"># Sample Data</span></pre></div>

<pre><code>##                mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4     21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag 21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710    22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
</code></pre>

<div class="highlight highlight-source-r"><pre>dim(<span class="pl-smi">mtcars</span>)</pre></div>

<pre><code>## [1] 32 11
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">mtcars</span><span class="pl-k">$</span><span class="pl-smi">cyl</span> <span class="pl-k">&lt;-</span> as.factor(<span class="pl-smi">mtcars</span><span class="pl-k">$</span><span class="pl-smi">cyl</span>)
<span class="pl-smi">mtcars</span><span class="pl-k">$</span><span class="pl-smi">vs</span> <span class="pl-k">&lt;-</span> as.factor(<span class="pl-smi">mtcars</span><span class="pl-k">$</span><span class="pl-smi">vs</span>)
<span class="pl-smi">mtcars</span><span class="pl-k">$</span><span class="pl-smi">am</span> <span class="pl-k">&lt;-</span> <span class="pl-k">factor</span>(<span class="pl-smi">mtcars</span><span class="pl-k">$</span><span class="pl-smi">am</span>)
<span class="pl-smi">mtcars</span><span class="pl-k">$</span><span class="pl-smi">gear</span> <span class="pl-k">&lt;-</span> <span class="pl-k">factor</span>(<span class="pl-smi">mtcars</span><span class="pl-k">$</span><span class="pl-smi">gear</span>)
<span class="pl-smi">mtcars</span><span class="pl-k">$</span><span class="pl-smi">carb</span> <span class="pl-k">&lt;-</span> <span class="pl-k">factor</span>(<span class="pl-smi">mtcars</span><span class="pl-k">$</span><span class="pl-smi">carb</span>)
attach(<span class="pl-smi">mtcars</span>)</pre></div>

<pre><code>## The following objects are masked from mtcars (pos = 3):
## 
##     am, carb, cyl, disp, drat, gear, hp, mpg, qsec, vs, wt
## 
## The following objects are masked from mtcars (pos = 4):
## 
##     am, carb, cyl, disp, drat, gear, hp, mpg, qsec, vs, wt
## 
## The following object is masked from package:ggplot2:
## 
##     mpg
</code></pre>

<p>Then, we do some basic exploratory data analyses. Please refer to the <strong>Appendix: Figures</strong> section for the plots. According to the box plot, we see that manual transmission yields higher values of MPG in general. And as for the pair graph, we can see some higher correlations between variables like "wt", "disp", "cyl" and "hp".  </p>

<h2><a id="user-content-inference" class="anchor" href="#inference" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Inference</h2>

<p>At this step, we make the null hypothesis as the MPG of the automatic and manual transmissions are from the same population (assuming the MPG has a normal distribution). We use the two sample T-test to show it.  </p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">result</span> <span class="pl-k">&lt;-</span> t.test(<span class="pl-smi">mpg</span> <span class="pl-k">~</span> <span class="pl-smi">am</span>)
<span class="pl-smi">result</span><span class="pl-k">$</span><span class="pl-smi">p.value</span></pre></div>

<pre><code>## [1] 0.001373638
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">result</span><span class="pl-k">$</span><span class="pl-smi">estimate</span></pre></div>

<pre><code>## mean in group 0 mean in group 1 
##        17.14737        24.39231
</code></pre>

<p>Since the p-value is 0.00137, we reject our null hypothesis. So, the automatic and manual transmissions are from different populations. And the mean for MPG of manual transmitted cars is about 7 more than that of automatic transmitted cars.  </p>

<h2><a id="user-content-regression-analysis" class="anchor" href="#regression-analysis" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Regression Analysis</h2>

<p>First, we fit the full model as the following.  </p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">fullModel</span> <span class="pl-k">&lt;-</span> lm(<span class="pl-smi">mpg</span> <span class="pl-k">~</span> ., <span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-smi">mtcars</span>)
summary(<span class="pl-smi">fullModel</span>) <span class="pl-c"># results hidden</span></pre></div>

<p>This model has the Residual standard error as 2.833 on 15 degrees of freedom. And the Adjusted R-squared value is 0.779, which means that the model can explain about 78% of the variance of the MPG variable. However, none of the coefficients are significant at 0.05 significant level.  </p>

<p>Then, we use backward selection to select some statistically significant variables.  </p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">stepModel</span> <span class="pl-k">&lt;-</span> step(<span class="pl-smi">fullModel</span>, <span class="pl-v">k</span><span class="pl-k">=</span>log(nrow(<span class="pl-smi">mtcars</span>)))
summary(<span class="pl-smi">stepModel</span>) <span class="pl-c"># results hidden</span></pre></div>

<p>This model is "mpg ~ wt + qsec + am". It has the Residual standard error as 2.459 on 28 degrees of freedom. And the Adjusted R-squared value is 0.8336, which means that the model can explain about 83% of the variance of the MPG variable. All of the coefficients are significant at 0.05 significant level.    </p>

<p>Please refer to the <strong>Appendix: Figures</strong> section for the plots again. According to the scatter plot, it indicates that there appear to be an interaction term between "wt" variable and "am" variable, since automatic cars tend to weigh heavier than manual cars. Thus, we have the following model including the interaction term:  </p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">amIntWtModel</span><span class="pl-k">&lt;-</span>lm(<span class="pl-smi">mpg</span> <span class="pl-k">~</span> <span class="pl-smi">wt</span> <span class="pl-k">+</span> <span class="pl-smi">qsec</span> <span class="pl-k">+</span> <span class="pl-smi">am</span> <span class="pl-k">+</span> <span class="pl-smi">wt</span><span class="pl-k">:</span><span class="pl-smi">am</span>, <span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-smi">mtcars</span>)
summary(<span class="pl-smi">amIntWtModel</span>) <span class="pl-c"># results hidden</span></pre></div>

<p>This model has the Residual standard error as 2.084 on 27 degrees of freedom. And the Adjusted R-squared value is 0.8804, which means that the model can explain about 88% of the variance of the MPG variable. All of the coefficients are significant at 0.05 significant level. This is a pretty good one.  </p>

<p>Next, we fit the simple model with MPG as the outcome variable and Transmission as the predictor variable.  </p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">amModel</span><span class="pl-k">&lt;-</span>lm(<span class="pl-smi">mpg</span> <span class="pl-k">~</span> <span class="pl-smi">am</span>, <span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-smi">mtcars</span>)
summary(<span class="pl-smi">amModel</span>) <span class="pl-c"># results hidden</span></pre></div>

<p>It shows that on average, a car has 17.147 mpg with automatic transmission, and if it is manual transmission, 7.245 mpg is increased. This model has the Residual standard error as 4.902 on 30 degrees of freedom. And the Adjusted R-squared value is 0.3385, which means that the model can explain about 34% of the variance of the MPG variable. The low Adjusted R-squared value also indicates that we need to add other variables to the model.  </p>

<p>Finally, we select the final model.  </p>

<div class="highlight highlight-source-r"><pre>anova(<span class="pl-smi">amModel</span>, <span class="pl-smi">stepModel</span>, <span class="pl-smi">fullModel</span>, <span class="pl-smi">amIntWtModel</span>) 
confint(<span class="pl-smi">amIntWtModel</span>) <span class="pl-c"># results hidden</span></pre></div>

<p>We end up selecting the model with the highest Adjusted R-squared value, "mpg ~ wt + qsec + am + wt:am".  </p>

<div class="highlight highlight-source-r"><pre>summary(<span class="pl-smi">amIntWtModel</span>)<span class="pl-k">$</span><span class="pl-smi">coef</span></pre></div>

<pre><code>##              Estimate Std. Error   t value     Pr(&gt;|t|)
## (Intercept)  9.723053  5.8990407  1.648243 0.1108925394
## wt          -2.936531  0.6660253 -4.409038 0.0001488947
## qsec         1.016974  0.2520152  4.035366 0.0004030165
## am1         14.079428  3.4352512  4.098515 0.0003408693
## wt:am1      -4.141376  1.1968119 -3.460340 0.0018085763
</code></pre>

<p>Thus, the result shows that when "wt" (weight lb/1000) and "qsec" (1/4 mile time) remain constant, cars with manual transmission add 14.079 + (-4.141)*wt more MPG (miles per gallon) on average than cars with automatic transmission. That is, a manual transmitted car that weighs 2000 lbs have 5.797 more MPG than an automatic transmitted car that has both the same weight and 1/4 mile time.  </p>

<h2><a id="user-content-residual-analysis-and-diagnostics" class="anchor" href="#residual-analysis-and-diagnostics" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Residual Analysis and Diagnostics</h2>

<p>Please refer to the <strong>Appendix: Figures</strong> section for the plots. According to the residual plots, we can verify the following underlying assumptions:<br>
1. The Residuals vs. Fitted plot shows no consistent pattern, supporting the accuracy of the independence assumption.<br>
2. The Normal Q-Q plot indicates that the residuals are normally distributed because the points lie closely to the line.<br>
3. The Scale-Location plot confirms the constant variance assumption, as the points are randomly distributed.<br>
4. The Residuals vs. Leverage argues that no outliers are present, as all values fall well within the 0.5 bands.  </p>

<p>As for the Dfbetas, the measure of how much an observation has effected the estimate of a regression coefficient, we get the following result:  </p>

<div class="highlight highlight-source-r"><pre>sum((abs(dfbetas(<span class="pl-smi">amIntWtModel</span>)))<span class="pl-k">&gt;</span><span class="pl-c1">1</span>)</pre></div>

<pre><code>## [1] 0
</code></pre>

<p>Therefore, the above analyses meet all basic assumptions of linear regression and well answer the questions.  </p>

<h2><a id="user-content-appendix-figures" class="anchor" href="#appendix-figures" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Appendix: Figures</h2>

<ol>
<li>Boxplot of MPG vs. Transmission<br></li>
</ol>

<div class="highlight highlight-source-r"><pre>boxplot(<span class="pl-smi">mpg</span> <span class="pl-k">~</span> <span class="pl-smi">am</span>, <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Transmission (0 = Automatic, 1 = Manual)<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>MPG<span class="pl-pds">"</span></span>,
        <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Boxplot of MPG vs. Transmission<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/amit/Coursera-Regression-Models/blob/master/motor_trend_project/figure/unnamed-chunk-10-1.png" target="_blank"><img src="/amit/Coursera-Regression-Models/raw/master/motor_trend_project/figure/unnamed-chunk-10-1.png" alt="plot of chunk unnamed-chunk-10" style="max-width:100%;"></a><br>
2. Pair Graph of Motor Trend Car Road Tests  </p>

<div class="highlight highlight-source-r"><pre>pairs(<span class="pl-smi">mtcars</span>, <span class="pl-v">panel</span><span class="pl-k">=</span><span class="pl-smi">panel.smooth</span>, <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Pair Graph of Motor Trend Car Road Tests<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/amit/Coursera-Regression-Models/blob/master/motor_trend_project/figure/unnamed-chunk-11-1.png" target="_blank"><img src="/amit/Coursera-Regression-Models/raw/master/motor_trend_project/figure/unnamed-chunk-11-1.png" alt="plot of chunk unnamed-chunk-11" style="max-width:100%;"></a><br>
3. Scatter Plot of MPG vs. Weight by Transmission  </p>

<div class="highlight highlight-source-r"><pre>ggplot(<span class="pl-smi">mtcars</span>, aes(<span class="pl-v">x</span><span class="pl-k">=</span><span class="pl-smi">wt</span>, <span class="pl-v">y</span><span class="pl-k">=</span><span class="pl-smi">mpg</span>, <span class="pl-v">group</span><span class="pl-k">=</span><span class="pl-smi">am</span>, <span class="pl-v">color</span><span class="pl-k">=</span><span class="pl-smi">am</span>, <span class="pl-v">height</span><span class="pl-k">=</span><span class="pl-c1">3</span>, <span class="pl-v">width</span><span class="pl-k">=</span><span class="pl-c1">3</span>)) <span class="pl-k">+</span> geom_point() <span class="pl-k">+</span>  
scale_colour_discrete(<span class="pl-v">labels</span><span class="pl-k">=</span>c(<span class="pl-s"><span class="pl-pds">"</span>Automatic<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Manual<span class="pl-pds">"</span></span>)) <span class="pl-k">+</span> 
xlab(<span class="pl-s"><span class="pl-pds">"</span>weight<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> ggtitle(<span class="pl-s"><span class="pl-pds">"</span>Scatter Plot of MPG vs. Weight by Transmission<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/amit/Coursera-Regression-Models/blob/master/motor_trend_project/figure/unnamed-chunk-12-1.png" target="_blank"><img src="/amit/Coursera-Regression-Models/raw/master/motor_trend_project/figure/unnamed-chunk-12-1.png" alt="plot of chunk unnamed-chunk-12" style="max-width:100%;"></a><br>
4. Residual Plots</p>

<div class="highlight highlight-source-r"><pre>par(<span class="pl-v">mfrow</span> <span class="pl-k">=</span> c(<span class="pl-c1">2</span>, <span class="pl-c1">2</span>))
plot(<span class="pl-smi">amIntWtModel</span>)</pre></div>

<p><a href="/amit/Coursera-Regression-Models/blob/master/motor_trend_project/figure/unnamed-chunk-13-1.png" target="_blank"><img src="/amit/Coursera-Regression-Models/raw/master/motor_trend_project/figure/unnamed-chunk-13-1.png" alt="plot of chunk unnamed-chunk-13" style="max-width:100%;"></a> </p>
</article>
  </div>

</div>

<button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="hidden">Jump to Line</button>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop"></div>
</div>


    </div>
  </div>

    </div>

        <div class="container site-footer-container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage" class="site-footer-mark" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59 0.4 0.07 0.55-0.17 0.55-0.38 0-0.19-0.01-0.82-0.01-1.49-2.01 0.37-2.53-0.49-2.69-0.94-0.09-0.23-0.48-0.94-0.82-1.13-0.28-0.15-0.68-0.52-0.01-0.53 0.63-0.01 1.08 0.58 1.23 0.82 0.72 1.21 1.87 0.87 2.33 0.66 0.07-0.52 0.28-0.87 0.51-1.07-1.78-0.2-3.64-0.89-3.64-3.95 0-0.87 0.31-1.59 0.82-2.15-0.08-0.2-0.36-1.02 0.08-2.12 0 0 0.67-0.21 2.2 0.82 0.64-0.18 1.32-0.27 2-0.27 0.68 0 1.36 0.09 2 0.27 1.53-1.04 2.2-0.82 2.2-0.82 0.44 1.1 0.16 1.92 0.08 2.12 0.51 0.56 0.82 1.27 0.82 2.15 0 3.07-1.87 3.75-3.65 3.95 0.29 0.25 0.54 0.73 0.54 1.48 0 1.07-0.01 1.93-0.01 2.2 0 0.21 0.15 0.46 0.55 0.38C13.71 14.53 16 11.53 16 8 16 3.58 12.42 0 8 0z"></path></svg>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2016 <span title="0.07745s from github-fe151-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    

    <div id="ajax-error-message" class="ajax-error-message flash flash-error">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15.72 12.5l-6.85-11.98C8.69 0.21 8.36 0.02 8 0.02s-0.69 0.19-0.87 0.5l-6.85 11.98c-0.18 0.31-0.18 0.69 0 1C0.47 13.81 0.8 14 1.15 14h13.7c0.36 0 0.69-0.19 0.86-0.5S15.89 12.81 15.72 12.5zM9 12H7V10h2V12zM9 9H7V5h2V9z"></path></svg>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
      </button>
      Something went wrong with that request. Please try again.
    </div>


      
      <script crossorigin="anonymous" integrity="sha256-hR3lVUbYeteG8+/vO1Y0+PikDWf6bUT4VNnpl2fpyaI=" src="https://assets-cdn.github.com/assets/frameworks-851de55546d87ad786f3efef3b5634f8f8a40d67fa6d44f854d9e99767e9c9a2.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-mm3jxdPdk82dZjim0bzCfrfL+a/dCCdx6pAPmZZZeiQ=" src="https://assets-cdn.github.com/assets/github-9a6de3c5d3dd93cd9d6638a6d1bcc27eb7cbf9afdd082771ea900f9996597a24.js"></script>
      
      
      
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15.72 12.5l-6.85-11.98C8.69 0.21 8.36 0.02 8 0.02s-0.69 0.19-0.87 0.5l-6.85 11.98c-0.18 0.31-0.18 0.69 0 1C0.47 13.81 0.8 14 1.15 14h13.7c0.36 0 0.69-0.19 0.86-0.5S15.89 12.81 15.72 12.5zM9 12H7V10h2V12zM9 9H7V5h2V9z"></path></svg>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
    <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
    </button>
  </div>
</div>

  </body>
</html>

