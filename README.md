





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-521cbf980c80.css" media="all" rel="stylesheet" />
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-f75b395c95ee.css" media="all" rel="stylesheet" />
  
  
  
  

  <meta name="viewport" content="width=device-width">
  
  <title>bootstrap/README.md at v4-dev · twbs/bootstrap</title>
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta content="https://avatars3.githubusercontent.com/u/2918581?s=400&amp;v=4" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="twbs/bootstrap" property="og:title" /><meta content="https://github.com/twbs/bootstrap" property="og:url" /><meta content="bootstrap - The most popular HTML, CSS, and JavaScript framework for developing responsive, mobile first projects on the web." property="og:description" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6MjQ0MzM5MTM2OjY2Nzg3YzcyMjk2OGFhMzE1MWRlYTRhMTgzNWRiODg4NjQzNTM1ODkxOWY3MzNiODg1MDEwYmQ5OTZmM2U1Zjk=--fecfd0af9878cf2e1c5ad2735f8d68694c5695db">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="CE50:7FDC:71514C:BF9A72:5A7091D8" data-pjax-transient>
  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
  <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
  <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="https://collector.githubapp.com/github-external/browser_event" name="octolytics-event-url" /><meta content="CE50:7FDC:71514C:BF9A72:5A7091D8" name="octolytics-dimension-request_id" /><meta content="iad" name="octolytics-dimension-region_edge" /><meta content="iad" name="octolytics-dimension-region_render" /><meta content="35961747" name="octolytics-actor-id" /><meta content="LotusApp" name="octolytics-actor-login" /><meta content="8d3a1ef1a11c127acf1b7d4f5417275e3729cc705fd3ba4315ac5752321ffbe2" name="octolytics-actor-hash" />
<meta content="https://github.com/hydro_browser_events" name="hydro-events-url" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />




  <meta class="js-ga-set" name="dimension1" content="Logged In">


  

      <meta name="hostname" content="github.com">
  <meta name="user-login" content="LotusApp">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="ZjlhMDNjODhhYjczMjhhNjg3ZTQ5NGMxYzI1NWU2YWY0ZmYyZTUwYzliNTg4MzlhM2NmOGIxZmI4Njk4ZDQzMXx7InJlbW90ZV9hZGRyZXNzIjoiODQuMTgyLjYzLjIzMCIsInJlcXVlc3RfaWQiOiJDRTUwOjdGREM6NzE1MTRDOkJGOUE3Mjo1QTcwOTFEOCIsInRpbWVzdGFtcCI6MTUxNzMyNjgwOSwiaG9zdCI6ImdpdGh1Yi5jb20ifQ==">

    <meta name="enabled-features" content="UNIVERSE_BANNER,MULTIPLE_ATTRIBUTION,FREE_TRIALS,MARKETPLACE_HERO_CARD_UPLOADER,CONTRIBUTOR_FLAGGED_CONTENT">

  <meta name="html-safe-nonce" content="aad1985714eba3a550485a8efdbcf1f04c5875ad">

  <meta http-equiv="x-pjax-version" content="2ec2e5bba9c4872d5bfe40441b87cd01">
  

      <link href="https://github.com/twbs/bootstrap/commits/v4-dev.atom" rel="alternate" title="Recent Commits to bootstrap:v4-dev" type="application/atom+xml">

  <meta name="description" content="bootstrap - The most popular HTML, CSS, and JavaScript framework for developing responsive, mobile first projects on the web.">
  <meta name="go-import" content="github.com/twbs/bootstrap git https://github.com/twbs/bootstrap.git">

  <meta content="2918581" name="octolytics-dimension-user_id" /><meta content="twbs" name="octolytics-dimension-user_login" /><meta content="2126244" name="octolytics-dimension-repository_id" /><meta content="twbs/bootstrap" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="2126244" name="octolytics-dimension-repository_network_root_id" /><meta content="twbs/bootstrap" name="octolytics-dimension-repository_network_root_nwo" /><meta content="false" name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" />


    <link rel="canonical" href="https://github.com/twbs/bootstrap/blob/v4-dev/README.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">

  <link rel="apple-touch-icon" href="/apple-touch-icon.png">
  <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon-180x180.png">


  </head>

  <body class="logged-in env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="bg-black text-white p-3 show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    



        
<header class="Header  f5" role="banner">
  <div class="d-flex px-3 flex-justify-between container-lg">
    <div class="d-flex flex-justify-between">
      <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="32" version="1.1" viewBox="0 0 16 16" width="32"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>


    </div>

    <div class="HeaderMenu d-flex flex-justify-between flex-auto">
      <div class="d-flex">
            <div class="">
              <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/twbs/bootstrap/search" class="js-site-search-form" data-scoped-search-url="/twbs/bootstrap/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
        <a href="/twbs/bootstrap/blob/v4-dev/README.md" class="header-search-scope no-underline">This repository</a>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        value=""
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
        <input type="hidden" class="js-site-search-type-field" name="type" >
    </label>
</form></div>

            </div>

          <ul class="d-flex pl-2 flex-items-center text-bold list-style-none" role="navigation">
            <li>
              <a href="/pulls" aria-label="Pull requests you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
                Pull requests
</a>            </li>
            <li>
              <a href="/issues" aria-label="Issues you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
                Issues
</a>            </li>
                <li>
                  <a href="/marketplace" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-selected-links=" /marketplace">
                    Marketplace
</a>                </li>
            <li>
              <a href="/explore" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore">
                Explore
</a>            </li>
          </ul>
      </div>

      <div class="d-flex">
        
<ul class="user-nav d-flex flex-items-center list-style-none" id="user-links">
  <li class="dropdown js-menu-container">
    <span class="d-inline-block  px-2">
      

    </span>
  </li>

  <li class="dropdown js-menu-container">
    <details class="dropdown-details details-reset js-dropdown-details d-flex px-2 flex-items-center">
      <summary class="HeaderNavlink"
         aria-label="Create new…"
         data-ga-click="Header, create new, icon:add">
        <svg aria-hidden="true" class="octicon octicon-plus float-left mr-1 mt-1" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"/></svg>
        <span class="dropdown-caret mt-1"></span>
      </summary>

      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="twbs/bootstrap">This repository</span>
  </div>
    <a class="dropdown-item" href="/twbs/bootstrap/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </details>
  </li>

  <li class="dropdown js-menu-container">

    <details class="dropdown-details details-reset js-dropdown-details d-flex pl-2 flex-items-center">
      <summary class="HeaderNavlink name mt-1"
        aria-label="View profile and more"
        data-ga-click="Header, show menu, icon:avatar">
        <img alt="@LotusApp" class="avatar float-left mr-1" src="https://avatars3.githubusercontent.com/u/35961747?s=40&amp;v=4" height="20" width="20">
        <span class="dropdown-caret"></span>
      </summary>

      <ul class="dropdown-menu dropdown-menu-sw">
        <li class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">LotusApp</strong>
        </li>

        <li class="dropdown-divider"></li>

        <li><a class="dropdown-item" href="/LotusApp" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a></li>
        <li><a class="dropdown-item" href="/LotusApp?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a></li>
          <li><a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, your gists, text:your gists">Your Gists</a></li>

        <li class="dropdown-divider"></li>

        <li><a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a></li>

        <li><a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a></li>

        <li><!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="sFEeoDc8Tr9TVDWPVCz65Z/BkDaU+HHkqGyyKTEbJtrBE+TEjZSoaEhqBQJww10YZ8KZoCLdgayjbxWI9XyicQ==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
        </form></li>
      </ul>
    </details>
  </li>
</ul>


        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="sr-only right-0" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="KPFXRI5zmq+PF4W9Q4ArCP8YmRsKQwmu4el9EQy+UZ9Zs60gNNt8eJQptTBnb4z1BxuQjbxm+ebq6tqwyNnVNA==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </div>
</header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main" class="application-main ">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <div id="js-repo-pjax-container" data-pjax-container >
      




  



  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav  ">
    <div class="repohead-details-container clearfix container">

      <ul class="pagehead-actions">
  <li>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="vN62bwtTRplBHatzrGJg7jF5BpySuxqDot4d4DZb+fUX6I+Zslf59iUDJ/gpqQ/l0ZDgqGS4O+HCeXtoeNB7cQ==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="2126244" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/twbs/bootstrap/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target"
            role="button"
            aria-haspopup="true"
            aria-expanded="false"
            aria-label="Toggle repository notifications menu"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
                <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                Watch
            </span>
          </a>
          <a class="social-count js-social-count"
            href="/twbs/bootstrap/watchers"
            aria-label="7253 users are watching this repository">
            7,253
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                        Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
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
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/twbs/bootstrap/unstar" class="starred js-social-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="61MPVDJB8+38Kua/MHFb5p+A5MIRR1jdMFcUcpQ1VqnMIBQA3vBFsVJaIgbW5g3IyEx1PdwmaZp59HRmT3uhvg==" /></div>
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar twbs/bootstrap"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/twbs/bootstrap/stargazers"
           aria-label="121235 users starred this repository">
          121,235
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/twbs/bootstrap/star" class="unstarred js-social-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="tc6CtMmzsUG3ba566yQX0OL+j32oHokrDcb77VU2dtF+yxb94x+p1FO0UhB4VB/scdNF3YVe7cYHyn+IeDDcXA==" /></div>
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star twbs/bootstrap"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/twbs/bootstrap/stargazers"
           aria-label="121235 users starred this repository">
          121,235
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/twbs/bootstrap/fork" class="btn-with-count" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="nalwQnW6ZcddyOqS/sIRms6AZQQAcffcW+pqHLShh6Zj0ZHadNeuaEwPCpdcYnqkB63PlAN71KXrk3L4st30Vw==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of twbs/bootstrap to your account"
                aria-label="Fork your own copy of twbs/bootstrap to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
            </button>
</form>
    <a href="/twbs/bootstrap/network" class="social-count"
       aria-label="57380 users forked this repository">
      57,380
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/twbs" class="url fn" rel="author">twbs</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/twbs/bootstrap" data-pjax="#js-repo-pjax-container">bootstrap</a></strong>

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/twbs/bootstrap" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /twbs/bootstrap" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/twbs/bootstrap/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /twbs/bootstrap/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">299</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/twbs/bootstrap/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /twbs/bootstrap/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">86</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/twbs/bootstrap/projects" class="js-selected-navigation-item reponav-item" data-hotkey="g b" data-selected-links="repo_projects new_repo_project repo_project /twbs/bootstrap/projects">
      <svg aria-hidden="true" class="octicon octicon-project" height="16" version="1.1" viewBox="0 0 15 16" width="15"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >5</span>
</a>


  <a href="/twbs/bootstrap/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse /twbs/bootstrap/pulse">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Insights
</a>

</nav>


  </div>

<div class="container new-discussion-timeline experiment-repo-nav  ">
  <div class="repository-content ">

    
  <a href="/twbs/bootstrap/blob/0a4c0a527ddc0e0dc61c8134c44f1460e5bd233f/README.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:dffcd1bf89110ad9ae8b2ff7f5a0317e -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">v4-dev</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
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


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/add-js-helpers/README.md"
               data-name="add-js-helpers"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                add-js-helpers
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/bardiharborow-icons/README.md"
               data-name="bardiharborow-icons"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                bardiharborow-icons
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/boom-toasted/README.md"
               data-name="boom-toasted"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                boom-toasted
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/custom-select-inline-width/README.md"
               data-name="custom-select-inline-width"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                custom-select-inline-width
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/dashboard-table/README.md"
               data-name="dashboard-table"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                dashboard-table
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/deprecate-hover-mixin/README.md"
               data-name="deprecate-hover-mixin"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                deprecate-hover-mixin
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/disabled-custom-checks/README.md"
               data-name="disabled-custom-checks"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                disabled-custom-checks
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/extend-docs/README.md"
               data-name="extend-docs"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                extend-docs
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/flex-checks/README.md"
               data-name="flex-checks"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                flex-checks
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/gh-pages/README.md"
               data-name="gh-pages"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                gh-pages
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/highlight-taps/README.md"
               data-name="highlight-taps"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                highlight-taps
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/input-group-file-browse-button/README.md"
               data-name="input-group-file-browse-button"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                input-group-file-browse-button
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/input-group-tests/README.md"
               data-name="input-group-tests"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                input-group-tests
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/input-group-text-grow/README.md"
               data-name="input-group-text-grow"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                input-group-text-grow
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/outline-active-focus/README.md"
               data-name="outline-active-focus"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                outline-active-focus
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/pagination-focus/README.md"
               data-name="pagination-focus"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                pagination-focus
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/relative-columns/README.md"
               data-name="relative-columns"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                relative-columns
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/show-all-sidebar/README.md"
               data-name="show-all-sidebar"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                show-all-sidebar
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/spinner/README.md"
               data-name="spinner"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                spinner
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/sr-only-update/README.md"
               data-name="sr-only-update"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                sr-only-update
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/theming-docs-update/README.md"
               data-name="theming-docs-update"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                theming-docs-update
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/undo-22740/README.md"
               data-name="undo-22740"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                undo-22740
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v3-dev-xmr-col-12-fw/README.md"
               data-name="v3-dev-xmr-col-12-fw"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v3-dev-xmr-col-12-fw
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v3-dev/README.md"
               data-name="v3-dev"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v3-dev
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v3.4.0-dev/README.md"
               data-name="v3.4.0-dev"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v3.4.0-dev
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-carousel-touch/README.md"
               data-name="v4-carousel-touch"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-carousel-touch
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-collapse-flex/README.md"
               data-name="v4-collapse-flex"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-collapse-flex
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-dev-andres-adds-color-yiq-variable/README.md"
               data-name="v4-dev-andres-adds-color-yiq-variable"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-dev-andres-adds-color-yiq-variable
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-dev-andres-navbar-hardcoded-padding/README.md"
               data-name="v4-dev-andres-navbar-hardcoded-padding"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-dev-andres-navbar-hardcoded-padding
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-dev-andres-table-active-state/README.md"
               data-name="v4-dev-andres-table-active-state"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-dev-andres-table-active-state
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-dev-johann-shadow/README.md"
               data-name="v4-dev-johann-shadow"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-dev-johann-shadow
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-dev-xmr-broken-link-checker/README.md"
               data-name="v4-dev-xmr-broken-link-checker"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-dev-xmr-broken-link-checker
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-dev-xmr-hugo/README.md"
               data-name="v4-dev-xmr-hugo"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-dev-xmr-hugo
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-dev-xmr-vnu/README.md"
               data-name="v4-dev-xmr-vnu"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-dev-xmr-vnu
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/twbs/bootstrap/blob/v4-dev/README.md"
               data-name="v4-dev"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-dev
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-dropdown-display/README.md"
               data-name="v4-dropdown-display"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-dropdown-display
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-navbar-lever/README.md"
               data-name="v4-navbar-lever"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-navbar-lever
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/v4-without-jquery/README.md"
               data-name="v4-without-jquery"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                v4-without-jquery
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/validation-required/README.md"
               data-name="validation-required"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                validation-required
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/validation-tooltip-example/README.md"
               data-name="validation-tooltip-example"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                validation-tooltip-example
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/twbs/bootstrap/blob/webpack/README.md"
               data-name="webpack"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                webpack
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v4.0.0/README.md"
              data-name="v4.0.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0">
                v4.0.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v4.0.0-beta.3/README.md"
              data-name="v4.0.0-beta.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta.3">
                v4.0.0-beta.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v4.0.0-beta.2/README.md"
              data-name="v4.0.0-beta.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta.2">
                v4.0.0-beta.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v4.0.0-beta/README.md"
              data-name="v4.0.0-beta"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta">
                v4.0.0-beta
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v4.0.0-alpha.6/README.md"
              data-name="v4.0.0-alpha.6"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-alpha.6">
                v4.0.0-alpha.6
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v4.0.0-alpha.5/README.md"
              data-name="v4.0.0-alpha.5"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-alpha.5">
                v4.0.0-alpha.5
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v4.0.0-alpha.4/README.md"
              data-name="v4.0.0-alpha.4"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-alpha.4">
                v4.0.0-alpha.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v4.0.0-alpha.3/README.md"
              data-name="v4.0.0-alpha.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-alpha.3">
                v4.0.0-alpha.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v4.0.0-alpha.2/README.md"
              data-name="v4.0.0-alpha.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-alpha.2">
                v4.0.0-alpha.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v4.0.0-alpha/README.md"
              data-name="v4.0.0-alpha"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-alpha">
                v4.0.0-alpha
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.3.7/README.md"
              data-name="v3.3.7"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.7">
                v3.3.7
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.3.6/README.md"
              data-name="v3.3.6"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.6">
                v3.3.6
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.3.5/README.md"
              data-name="v3.3.5"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.5">
                v3.3.5
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.3.4/README.md"
              data-name="v3.3.4"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.4">
                v3.3.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.3.2/README.md"
              data-name="v3.3.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.2">
                v3.3.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.3.1/README.md"
              data-name="v3.3.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.1">
                v3.3.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.3.0/README.md"
              data-name="v3.3.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.0">
                v3.3.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.2.0/README.md"
              data-name="v3.2.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.2.0">
                v3.2.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.1.1/README.md"
              data-name="v3.1.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.1.1">
                v3.1.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.1.0/README.md"
              data-name="v3.1.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.1.0">
                v3.1.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.0.3/README.md"
              data-name="v3.0.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.3">
                v3.0.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.0.2/README.md"
              data-name="v3.0.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.2">
                v3.0.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.0.1/README.md"
              data-name="v3.0.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.1">
                v3.0.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.0.0/README.md"
              data-name="v3.0.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.0">
                v3.0.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.0.0-rc.2/README.md"
              data-name="v3.0.0-rc.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.0-rc.2">
                v3.0.0-rc.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v3.0.0-rc1/README.md"
              data-name="v3.0.0-rc1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.0-rc1">
                v3.0.0-rc1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.3.2/README.md"
              data-name="v2.3.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.3.2">
                v2.3.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.3.1/README.md"
              data-name="v2.3.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.3.1">
                v2.3.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.3.0/README.md"
              data-name="v2.3.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.3.0">
                v2.3.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.2.2/README.md"
              data-name="v2.2.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.2.2">
                v2.2.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.2.1/README.md"
              data-name="v2.2.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.2.1">
                v2.2.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.2.0/README.md"
              data-name="v2.2.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.2.0">
                v2.2.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.1.1/README.md"
              data-name="v2.1.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.1.1">
                v2.1.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.1.0/README.md"
              data-name="v2.1.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.1.0">
                v2.1.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.0.4/README.md"
              data-name="v2.0.4"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.0.4">
                v2.0.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.0.3/README.md"
              data-name="v2.0.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.0.3">
                v2.0.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.0.2/README.md"
              data-name="v2.0.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.0.2">
                v2.0.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.0.1/README.md"
              data-name="v2.0.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.0.1">
                v2.0.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v2.0.0/README.md"
              data-name="v2.0.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.0.0">
                v2.0.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v1.4.0/README.md"
              data-name="v1.4.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.4.0">
                v1.4.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v1.3.0/README.md"
              data-name="v1.3.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.3.0">
                v1.3.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v1.2.0/README.md"
              data-name="v1.2.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.2.0">
                v1.2.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v1.1.1/README.md"
              data-name="v1.1.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.1.1">
                v1.1.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v1.1.0/README.md"
              data-name="v1.1.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.1.0">
                v1.1.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/twbs/bootstrap/tree/v1.0.0/README.md"
              data-name="v1.0.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v1.0.0">
                v1.0.0
              </span>
            </a>
        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/twbs/bootstrap/find/v4-dev"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
    </div>
    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/twbs/bootstrap" data-pjax="true"><span>bootstrap</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
    </div>
  </div>


  
  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/twbs/bootstrap/commit/6b48747e61c1db92d9d65deb5ae3e62d1a89ff9e" data-pjax>
          6b48747
        </a>
        <relative-time datetime="2018-01-20T20:01:02Z">Jan 20, 2018</relative-time>
      </span>
      <div>
        <img alt="@vsn4ik" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/3757319?s=40&amp;v=4" width="20" />
        <a href="/vsn4ik" class="user-mention" rel="contributor">vsn4ik</a>
          <a href="/twbs/bootstrap/commit/6b48747e61c1db92d9d65deb5ae3e62d1a89ff9e" class="message" data-pjax="true" title="Remove -Pre from Nuget install">Remove -Pre from Nuget install</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>78</strong>
         contributors
      </button>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="mdo" href="/twbs/bootstrap/commits/v4-dev/README.md?author=mdo"><img alt="@mdo" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/98681?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="cvrebert" href="/twbs/bootstrap/commits/v4-dev/README.md?author=cvrebert"><img alt="@cvrebert" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/419884?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="fat" href="/twbs/bootstrap/commits/v4-dev/README.md?author=fat"><img alt="@fat" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/169705?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="XhmikosR" href="/twbs/bootstrap/commits/v4-dev/README.md?author=XhmikosR"><img alt="@XhmikosR" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/349621?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="vsn4ik" href="/twbs/bootstrap/commits/v4-dev/README.md?author=vsn4ik"><img alt="@vsn4ik" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/3757319?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="juthilo" href="/twbs/bootstrap/commits/v4-dev/README.md?author=juthilo"><img alt="@juthilo" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/3535675?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="supergibbs" href="/twbs/bootstrap/commits/v4-dev/README.md?author=supergibbs"><img alt="@supergibbs" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/1106331?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="bardiharborow" href="/twbs/bootstrap/commits/v4-dev/README.md?author=bardiharborow"><img alt="@bardiharborow" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/1073681?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="kkirsche" href="/twbs/bootstrap/commits/v4-dev/README.md?author=kkirsche"><img alt="@kkirsche" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/947110?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="Johann-S" href="/twbs/bootstrap/commits/v4-dev/README.md?author=Johann-S"><img alt="@Johann-S" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/1689750?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="alienlebarge" href="/twbs/bootstrap/commits/v4-dev/README.md?author=alienlebarge"><img alt="@alienlebarge" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/611234?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="caniszczyk" href="/twbs/bootstrap/commits/v4-dev/README.md?author=caniszczyk"><img alt="@caniszczyk" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/63777?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="jojobyte" href="/twbs/bootstrap/commits/v4-dev/README.md?author=jojobyte"><img alt="@jojobyte" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/184880?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="J2TeaM" href="/twbs/bootstrap/commits/v4-dev/README.md?author=J2TeaM"><img alt="@J2TeaM" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/5250117?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="vannitotaro" href="/twbs/bootstrap/commits/v4-dev/README.md?author=vannitotaro"><img alt="@vannitotaro" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/519343?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="Herst" href="/twbs/bootstrap/commits/v4-dev/README.md?author=Herst"><img alt="@Herst" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/1042176?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="akalicki" href="/twbs/bootstrap/commits/v4-dev/README.md?author=akalicki"><img alt="@akalicki" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/3604541?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="JCA122204" href="/twbs/bootstrap/commits/v4-dev/README.md?author=JCA122204"><img alt="@JCA122204" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/34488805?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="copynpaste" href="/twbs/bootstrap/commits/v4-dev/README.md?author=copynpaste"><img alt="@copynpaste" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/29928126?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="ggam" href="/twbs/bootstrap/commits/v4-dev/README.md?author=ggam"><img alt="@ggam" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/2109040?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="waynn" href="/twbs/bootstrap/commits/v4-dev/README.md?author=waynn"><img alt="@waynn" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/318137?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="tomByrer" href="/twbs/bootstrap/commits/v4-dev/README.md?author=tomByrer"><img alt="@tomByrer" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/1308419?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="tkrotoff" href="/twbs/bootstrap/commits/v4-dev/README.md?author=tkrotoff"><img alt="@tkrotoff" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/643434?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="thomas-mcdonald" href="/twbs/bootstrap/commits/v4-dev/README.md?author=thomas-mcdonald"><img alt="@thomas-mcdonald" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/197928?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="TannerNMO" href="/twbs/bootstrap/commits/v4-dev/README.md?author=TannerNMO"><img alt="@TannerNMO" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/1172859?s=40&amp;v=4" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="smaboshe" href="/twbs/bootstrap/commits/v4-dev/README.md?author=smaboshe"><img alt="@smaboshe" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/72755?s=40&amp;v=4" width="20" /> </a>

    <button type="button" data-facebox="#blob_contributors_box" class="btn-link others-text">and others</button>

    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@mdo" height="24" src="https://avatars2.githubusercontent.com/u/98681?s=48&amp;v=4" width="24" />
            <a href="/mdo">mdo</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@cvrebert" height="24" src="https://avatars2.githubusercontent.com/u/419884?s=48&amp;v=4" width="24" />
            <a href="/cvrebert">cvrebert</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@fat" height="24" src="https://avatars3.githubusercontent.com/u/169705?s=48&amp;v=4" width="24" />
            <a href="/fat">fat</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@XhmikosR" height="24" src="https://avatars3.githubusercontent.com/u/349621?s=48&amp;v=4" width="24" />
            <a href="/XhmikosR">XhmikosR</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@vsn4ik" height="24" src="https://avatars2.githubusercontent.com/u/3757319?s=48&amp;v=4" width="24" />
            <a href="/vsn4ik">vsn4ik</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@juthilo" height="24" src="https://avatars3.githubusercontent.com/u/3535675?s=48&amp;v=4" width="24" />
            <a href="/juthilo">juthilo</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@supergibbs" height="24" src="https://avatars2.githubusercontent.com/u/1106331?s=48&amp;v=4" width="24" />
            <a href="/supergibbs">supergibbs</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@bardiharborow" height="24" src="https://avatars1.githubusercontent.com/u/1073681?s=48&amp;v=4" width="24" />
            <a href="/bardiharborow">bardiharborow</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@kkirsche" height="24" src="https://avatars1.githubusercontent.com/u/947110?s=48&amp;v=4" width="24" />
            <a href="/kkirsche">kkirsche</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@Johann-S" height="24" src="https://avatars1.githubusercontent.com/u/1689750?s=48&amp;v=4" width="24" />
            <a href="/Johann-S">Johann-S</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@alienlebarge" height="24" src="https://avatars3.githubusercontent.com/u/611234?s=48&amp;v=4" width="24" />
            <a href="/alienlebarge">alienlebarge</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@caniszczyk" height="24" src="https://avatars1.githubusercontent.com/u/63777?s=48&amp;v=4" width="24" />
            <a href="/caniszczyk">caniszczyk</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jojobyte" height="24" src="https://avatars1.githubusercontent.com/u/184880?s=48&amp;v=4" width="24" />
            <a href="/jojobyte">jojobyte</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@J2TeaM" height="24" src="https://avatars1.githubusercontent.com/u/5250117?s=48&amp;v=4" width="24" />
            <a href="/J2TeaM">J2TeaM</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@vannitotaro" height="24" src="https://avatars2.githubusercontent.com/u/519343?s=48&amp;v=4" width="24" />
            <a href="/vannitotaro">vannitotaro</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@Herst" height="24" src="https://avatars3.githubusercontent.com/u/1042176?s=48&amp;v=4" width="24" />
            <a href="/Herst">Herst</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@akalicki" height="24" src="https://avatars3.githubusercontent.com/u/3604541?s=48&amp;v=4" width="24" />
            <a href="/akalicki">akalicki</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@JCA122204" height="24" src="https://avatars1.githubusercontent.com/u/34488805?s=48&amp;v=4" width="24" />
            <a href="/JCA122204">JCA122204</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@copynpaste" height="24" src="https://avatars3.githubusercontent.com/u/29928126?s=48&amp;v=4" width="24" />
            <a href="/copynpaste">copynpaste</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@ggam" height="24" src="https://avatars0.githubusercontent.com/u/2109040?s=48&amp;v=4" width="24" />
            <a href="/ggam">ggam</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@waynn" height="24" src="https://avatars3.githubusercontent.com/u/318137?s=48&amp;v=4" width="24" />
            <a href="/waynn">waynn</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@tomByrer" height="24" src="https://avatars1.githubusercontent.com/u/1308419?s=48&amp;v=4" width="24" />
            <a href="/tomByrer">tomByrer</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@tkrotoff" height="24" src="https://avatars1.githubusercontent.com/u/643434?s=48&amp;v=4" width="24" />
            <a href="/tkrotoff">tkrotoff</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@thomas-mcdonald" height="24" src="https://avatars2.githubusercontent.com/u/197928?s=48&amp;v=4" width="24" />
            <a href="/thomas-mcdonald">thomas-mcdonald</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@TannerNMO" height="24" src="https://avatars1.githubusercontent.com/u/1172859?s=48&amp;v=4" width="24" />
            <a href="/TannerNMO">TannerNMO</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@smaboshe" height="24" src="https://avatars2.githubusercontent.com/u/72755?s=48&amp;v=4" width="24" />
            <a href="/smaboshe">smaboshe</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@seriema" height="24" src="https://avatars1.githubusercontent.com/u/693684?s=48&amp;v=4" width="24" />
            <a href="/seriema">seriema</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@soffes" height="24" src="https://avatars3.githubusercontent.com/u/52870?s=48&amp;v=4" width="24" />
            <a href="/soffes">soffes</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@rustinlee" height="24" src="https://avatars2.githubusercontent.com/u/3959144?s=48&amp;v=4" width="24" />
            <a href="/rustinlee">rustinlee</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@royopa" height="24" src="https://avatars3.githubusercontent.com/u/442991?s=48&amp;v=4" width="24" />
            <a href="/royopa">royopa</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@rhodrykorb" height="24" src="https://avatars3.githubusercontent.com/u/968250?s=48&amp;v=4" width="24" />
            <a href="/rhodrykorb">rhodrykorb</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@rafaelstz" height="24" src="https://avatars3.githubusercontent.com/u/610598?s=48&amp;v=4" width="24" />
            <a href="/rafaelstz">rafaelstz</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@Devinsuit" height="24" src="https://avatars1.githubusercontent.com/u/11741306?s=48&amp;v=4" width="24" />
            <a href="/Devinsuit">Devinsuit</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@philfreo" height="24" src="https://avatars1.githubusercontent.com/u/97612?s=48&amp;v=4" width="24" />
            <a href="/philfreo">philfreo</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@parndt" height="24" src="https://avatars0.githubusercontent.com/u/10128?s=48&amp;v=4" width="24" />
            <a href="/parndt">parndt</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@nunoarruda" height="24" src="https://avatars1.githubusercontent.com/u/1189149?s=48&amp;v=4" width="24" />
            <a href="/nunoarruda">nunoarruda</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@nschonni" height="24" src="https://avatars2.githubusercontent.com/u/1297909?s=48&amp;v=4" width="24" />
            <a href="/nschonni">nschonni</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@mathiasose" height="24" src="https://avatars1.githubusercontent.com/u/2864935?s=48&amp;v=4" width="24" />
            <a href="/mathiasose">mathiasose</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@cba" height="24" src="https://avatars1.githubusercontent.com/u/33331734?s=48&amp;v=4" width="24" />
            <a href="/cba">cba</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@lipis" height="24" src="https://avatars0.githubusercontent.com/u/125676?s=48&amp;v=4" width="24" />
            <a href="/lipis">lipis</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@alundiak" height="24" src="https://avatars2.githubusercontent.com/u/2131633?s=48&amp;v=4" width="24" />
            <a href="/alundiak">alundiak</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@koenpunt" height="24" src="https://avatars2.githubusercontent.com/u/351038?s=48&amp;v=4" width="24" />
            <a href="/koenpunt">koenpunt</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jouve" height="24" src="https://avatars1.githubusercontent.com/u/1096799?s=48&amp;v=4" width="24" />
            <a href="/jouve">jouve</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@reversefold" height="24" src="https://avatars0.githubusercontent.com/u/100180?s=48&amp;v=4" width="24" />
            <a href="/reversefold">reversefold</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jpkleemans" height="24" src="https://avatars3.githubusercontent.com/u/5700014?s=48&amp;v=4" width="24" />
            <a href="/jpkleemans">jpkleemans</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jeroenvisser101" height="24" src="https://avatars3.githubusercontent.com/u/1941348?s=48&amp;v=4" width="24" />
            <a href="/jeroenvisser101">jeroenvisser101</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jfroom" height="24" src="https://avatars3.githubusercontent.com/u/943108?s=48&amp;v=4" width="24" />
            <a href="/jfroom">jfroom</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@JasonEtco" height="24" src="https://avatars3.githubusercontent.com/u/10660468?s=48&amp;v=4" width="24" />
            <a href="/JasonEtco">JasonEtco</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jackmu95" height="24" src="https://avatars0.githubusercontent.com/u/2737132?s=48&amp;v=4" width="24" />
            <a href="/jackmu95">jackmu95</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@splendido" height="24" src="https://avatars3.githubusercontent.com/u/6148980?s=48&amp;v=4" width="24" />
            <a href="/splendido">splendido</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@hnrch02" height="24" src="https://avatars1.githubusercontent.com/u/1068978?s=48&amp;v=4" width="24" />
            <a href="/hnrch02">hnrch02</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@hkdobrev" height="24" src="https://avatars0.githubusercontent.com/u/506129?s=48&amp;v=4" width="24" />
            <a href="/hkdobrev">hkdobrev</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@mortonfox" height="24" src="https://avatars0.githubusercontent.com/u/495892?s=48&amp;v=4" width="24" />
            <a href="/mortonfox">mortonfox</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@entozoon" height="24" src="https://avatars0.githubusercontent.com/u/5763772?s=48&amp;v=4" width="24" />
            <a href="/entozoon">entozoon</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@DHS" height="24" src="https://avatars3.githubusercontent.com/u/326442?s=48&amp;v=4" width="24" />
            <a href="/DHS">DHS</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@cowboy" height="24" src="https://avatars3.githubusercontent.com/u/54051?s=48&amp;v=4" width="24" />
            <a href="/cowboy">cowboy</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@Siecje" height="24" src="https://avatars3.githubusercontent.com/u/4069476?s=48&amp;v=4" width="24" />
            <a href="/Siecje">Siecje</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@strayobject" height="24" src="https://avatars1.githubusercontent.com/u/2257473?s=48&amp;v=4" width="24" />
            <a href="/strayobject">strayobject</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@hppycoder" height="24" src="https://avatars2.githubusercontent.com/u/541976?s=48&amp;v=4" width="24" />
            <a href="/hppycoder">hppycoder</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@bradly" height="24" src="https://avatars0.githubusercontent.com/u/4227?s=48&amp;v=4" width="24" />
            <a href="/bradly">bradly</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@bblokar" height="24" src="https://avatars1.githubusercontent.com/u/3136883?s=48&amp;v=4" width="24" />
            <a href="/bblokar">bblokar</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@bastienmoulia" height="24" src="https://avatars2.githubusercontent.com/u/686196?s=48&amp;v=4" width="24" />
            <a href="/bastienmoulia">bastienmoulia</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@xtoolkit" height="24" src="https://avatars1.githubusercontent.com/u/8210666?s=48&amp;v=4" width="24" />
            <a href="/xtoolkit">xtoolkit</a>
          </li>
      </ul>
    </div>
  </div>


  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/twbs/bootstrap/raw/v4-dev/README.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/twbs/bootstrap/blame/v4-dev/README.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b">Blame</a>
      <a href="/twbs/bootstrap/commits/v4-dev/README.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>


          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/twbs/bootstrap/edit/v4-dev/README.md" class="inline-form js-update-url-with-hash" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="JoZGTROdA1ozkQsrVYkAiUjk9UoxeIQxguyeVT7YF9UJO9G6CG7f8dG5c2eqgbgkcaQurzIOjKhvFpJOMttFvQ==" /></div>
            <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
              aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
              <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
            </button>
</form>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/twbs/bootstrap/delete/v4-dev/README.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="aMIcwDeWS3gGP1TVZ3rFgGvIDNr+0RUDKn4p14Vml3Dk5HnybzsqYG29z7PuoWEXXudIhXILVgvMFaqiwwlwWQ==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
</form>  </div>

  <div class="file-info">
      168 lines (116 sloc)
      <span class="file-info-divider"></span>
    8.85 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><p align="center">
  <a href="https://getbootstrap.com/" rel="nofollow">
    <img src="https://camo.githubusercontent.com/5d417873a11d7175ec40fc3af3c6cb024a531dd7/68747470733a2f2f676574626f6f7473747261702e636f6d2f6173736574732f6272616e642f626f6f7473747261702d736f6c69642e737667" alt="" width="72" height="72" data-canonical-src="https://getbootstrap.com/assets/brand/bootstrap-solid.svg" style="max-width:100%;">
  </a>
  </p><h3 align="center"><a href="#bootstrap" aria-hidden="true" class="anchor" id="user-content-bootstrap"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Bootstrap</h3>
  <p align="center">
    Sleek, intuitive, and powerful front-end framework for faster and easier web development.
    <br>
    <a href="https://getbootstrap.com/docs/4.0/" rel="nofollow"><strong>Explore Bootstrap docs »</strong></a>
    <br>
    <br>
    <a href="https://themes.getbootstrap.com/" rel="nofollow">Bootstrap Themes</a>
    ·
    <a href="https://jobs.getbootstrap.com/" rel="nofollow">Job Board</a>
    ·
    <a href="https://blog.getbootstrap.com/" rel="nofollow">Blog</a>
  </p>
<p></p>
<br>
<h2><a href="#table-of-contents" aria-hidden="true" class="anchor" id="user-content-table-of-contents"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Table of contents</h2>
<ul>
<li><a href="#quick-start">Quick start</a></li>
<li><a href="#status">Status</a></li>
<li><a href="#whats-included">What's included</a></li>
<li><a href="#bugs-and-feature-requests">Bugs and feature requests</a></li>
<li><a href="#documentation">Documentation</a></li>
<li><a href="#contributing">Contributing</a></li>
<li><a href="#community">Community</a></li>
<li><a href="#versioning">Versioning</a></li>
<li><a href="#creators">Creators</a></li>
<li><a href="#copyright-and-license">Copyright and license</a></li>
</ul>
<h2><a href="#quick-start" aria-hidden="true" class="anchor" id="user-content-quick-start"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Quick start</h2>
<p>Several quick start options are available:</p>
<ul>
<li><a href="https://github.com/twbs/bootstrap/archive/v4.0.0.zip">Download the latest release.</a></li>
<li>Clone the repo: <code>git clone https://github.com/twbs/bootstrap.git</code></li>
<li>Install with <a href="https://www.npmjs.com/" rel="nofollow">npm</a>: <code>npm install bootstrap</code></li>
<li>Install with <a href="https://yarnpkg.com/" rel="nofollow">yarn</a>: <code>yarn add bootstrap@4.0.0</code></li>
<li>Install with <a href="https://getcomposer.org/" rel="nofollow">Composer</a>: <code>composer require twbs/bootstrap:4.0.0</code></li>
<li>Install with <a href="https://www.nuget.org/" rel="nofollow">NuGet</a>: CSS: <code>Install-Package bootstrap</code> Sass: <code>Install-Package bootstrap.sass</code></li>
</ul>
<p>Read the <a href="https://getbootstrap.com/docs/4.0/getting-started/introduction/" rel="nofollow">Getting started page</a> for information on the framework contents, templates and examples, and more.</p>
<h2><a href="#status" aria-hidden="true" class="anchor" id="user-content-status"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Status</h2>
<p><a href="https://bootstrap-slack.herokuapp.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/b24a92612c39037a7fe712696b32ddf04d8ad970/68747470733a2f2f626f6f7473747261702d736c61636b2e6865726f6b756170702e636f6d2f62616467652e737667" alt="Slack" data-canonical-src="https://bootstrap-slack.herokuapp.com/badge.svg" style="max-width:100%;"></a>
<a href="https://travis-ci.org/twbs/bootstrap" rel="nofollow"><img src="https://camo.githubusercontent.com/db33fc85b8866c318001cc557163ab4dcd6b5d85/68747470733a2f2f696d672e736869656c64732e696f2f7472617669732f747762732f626f6f7473747261702f76342d6465762e737667" alt="Build Status" data-canonical-src="https://img.shields.io/travis/twbs/bootstrap/v4-dev.svg" style="max-width:100%;"></a>
<a href="https://www.npmjs.com/package/bootstrap" rel="nofollow"><img src="https://camo.githubusercontent.com/37040a3313caaeba028d2cb2d683fc803cc8ca06/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f626f6f7473747261702e737667" alt="npm version" data-canonical-src="https://img.shields.io/npm/v/bootstrap.svg" style="max-width:100%;"></a>
<a href="https://rubygems.org/gems/bootstrap" rel="nofollow"><img src="https://camo.githubusercontent.com/ed9b7c5f7b221809f320e7f020259b19e5dafc3d/68747470733a2f2f696d672e736869656c64732e696f2f67656d2f762f626f6f7473747261702e737667" alt="Gem version" data-canonical-src="https://img.shields.io/gem/v/bootstrap.svg" style="max-width:100%;"></a>
<a href="https://atmospherejs.com/twbs/bootstrap" rel="nofollow"><img src="https://camo.githubusercontent.com/acdfe59f064c6554fd5b71158970ba24ccfdf4c4/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6d6574656f722d74776273253341626f6f7473747261702d626c75652e737667" alt="Meteor Atmosphere" data-canonical-src="https://img.shields.io/badge/meteor-twbs%3Abootstrap-blue.svg" style="max-width:100%;"></a>
<a href="https://packagist.org/packages/twbs/bootstrap" rel="nofollow"><img src="https://camo.githubusercontent.com/924099d14bb66df79b2aa03f5fd10c24ec4a6720/68747470733a2f2f696d672e736869656c64732e696f2f7061636b61676973742f767072652f747762732f626f6f7473747261702e737667" alt="Packagist Prerelease" data-canonical-src="https://img.shields.io/packagist/vpre/twbs/bootstrap.svg" style="max-width:100%;"></a>
<a href="https://www.nuget.org/packages/bootstrap/absoluteLatest" rel="nofollow"><img src="https://camo.githubusercontent.com/5ec0effd84601cd1dc44e0c79d778030ba238907/68747470733a2f2f696d672e736869656c64732e696f2f6e756765742f767072652f626f6f7473747261702e737667" alt="NuGet" data-canonical-src="https://img.shields.io/nuget/vpre/bootstrap.svg" style="max-width:100%;"></a>
<a href="https://david-dm.org/twbs/bootstrap?type=peer" rel="nofollow"><img src="https://camo.githubusercontent.com/b8fa5d84f2112ce90170d37704d7b75e8c7a2639/68747470733a2f2f696d672e736869656c64732e696f2f64617669642f706565722f747762732f626f6f7473747261702e737667" alt="peerDependencies Status" data-canonical-src="https://img.shields.io/david/peer/twbs/bootstrap.svg" style="max-width:100%;"></a>
<a href="https://david-dm.org/twbs/bootstrap?type=dev" rel="nofollow"><img src="https://camo.githubusercontent.com/5bd79ff4565350259789b599873cf6d1396e112b/68747470733a2f2f696d672e736869656c64732e696f2f64617669642f6465762f747762732f626f6f7473747261702e737667" alt="devDependency Status" data-canonical-src="https://img.shields.io/david/dev/twbs/bootstrap.svg" style="max-width:100%;"></a>
<a href="https://github.com/twbs/bootstrap/tree/v4-dev/dist/css/bootstrap.min.css"><img src="https://camo.githubusercontent.com/be916c5938a3523d8aeb5dda970c6d870a5de6b5/687474703a2f2f696d672e626164676573697a652e696f2f747762732f626f6f7473747261702f76342d6465762f646973742f6373732f626f6f7473747261702e6d696e2e6373733f636f6d7072657373696f6e3d677a6970266c6162656c3d4353532b677a69702b73697a65" alt="CSS gzip size" data-canonical-src="http://img.badgesize.io/twbs/bootstrap/v4-dev/dist/css/bootstrap.min.css?compression=gzip&amp;label=CSS+gzip+size" style="max-width:100%;"></a>
<a href="https://github.com/twbs/bootstrap/tree/v4-dev/dist/js/bootstrap.min.js"><img src="https://camo.githubusercontent.com/6fa499176b6104e3c345902032811b3e69ec14fe/687474703a2f2f696d672e626164676573697a652e696f2f747762732f626f6f7473747261702f76342d6465762f646973742f6a732f626f6f7473747261702e6d696e2e6a733f636f6d7072657373696f6e3d677a6970266c6162656c3d4a532b677a69702b73697a65" alt="JS gzip size" data-canonical-src="http://img.badgesize.io/twbs/bootstrap/v4-dev/dist/js/bootstrap.min.js?compression=gzip&amp;label=JS+gzip+size" style="max-width:100%;"></a></p>
<p><a href="https://saucelabs.com/u/bootstrap" rel="nofollow"><img src="https://camo.githubusercontent.com/3e0aa93ee06f55b9d19d2209bd12bec39cc40cec/68747470733a2f2f73617563656c6162732e636f6d2f62726f777365722d6d61747269782f626f6f7473747261702e737667" alt="Sauce Labs Test Status" data-canonical-src="https://saucelabs.com/browser-matrix/bootstrap.svg" style="max-width:100%;"></a></p>
<h2><a href="#whats-included" aria-hidden="true" class="anchor" id="user-content-whats-included"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>What's included</h2>
<p>Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:</p>
<pre><code>bootstrap/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap.min.css.map
│   ├── bootstrap-grid.css
│   ├── bootstrap-grid.css.map
│   ├── bootstrap-grid.min.css
│   ├── bootstrap-grid.min.css.map
│   ├── bootstrap-reboot.css
│   ├── bootstrap-reboot.css.map
│   ├── bootstrap-reboot.min.css
│   └── bootstrap-reboot.min.css.map
└── js/
    ├── bootstrap.bundle.js
    ├── bootstrap.bundle.min.js
    ├── bootstrap.js
    └── bootstrap.min.js
</code></pre>
<p>We provide compiled CSS and JS (<code>bootstrap.*</code>), as well as compiled and minified CSS and JS (<code>bootstrap.min.*</code>). CSS <a href="https://developers.google.com/web/tools/chrome-devtools/debug/readability/source-maps" rel="nofollow">source maps</a> (<code>bootstrap.*.map</code>) are available for use with certain browsers' developer tools. Bundled JS files (<code>bootstrap.bundle.js</code> and minified <code>bootstrap.bundle.min.js</code>) include <a href="https://popper.js.org/" rel="nofollow">Popper</a>, but not <a href="https://jquery.com/" rel="nofollow">jQuery</a>.</p>
<h2><a href="#bugs-and-feature-requests" aria-hidden="true" class="anchor" id="user-content-bugs-and-feature-requests"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Bugs and feature requests</h2>
<p>Have a bug or a feature request? Please first read the <a href="https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md#using-the-issue-tracker">issue guidelines</a> and search for existing and closed issues. If your problem or idea is not addressed yet, <a href="https://github.com/twbs/bootstrap/issues/new">please open a new issue</a>.</p>
<h2><a href="#documentation" aria-hidden="true" class="anchor" id="user-content-documentation"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Documentation</h2>
<p>Bootstrap's documentation, included in this repo in the root directory, is built with <a href="https://jekyllrb.com/" rel="nofollow">Jekyll</a> and publicly hosted on GitHub Pages at <a href="https://getbootstrap.com/" rel="nofollow">https://getbootstrap.com/</a>. The docs may also be run locally.</p>
<p>Documentation search is powered by <a href="https://community.algolia.com/docsearch/" rel="nofollow">Algolia's DocSearch</a>. Working on our search? Be sure to set <code>debug: true</code> in the <code>_scripts.html</code> include.</p>
<h3><a href="#running-documentation-locally" aria-hidden="true" class="anchor" id="user-content-running-documentation-locally"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Running documentation locally</h3>
<ol>
<li>Run through the <a href="https://getbootstrap.com/docs/4.0/getting-started/build-tools/#tooling-setup" rel="nofollow">tooling setup</a> to install Jekyll (the site builder) and other Ruby dependencies with <code>bundle install</code>.</li>
<li>Run <code>npm install</code> to install Node.js dependencies.</li>
<li>Run <code>npm run test</code> (or a specific NPM script) to rebuild distributed CSS and JavaScript files, as well as our docs assets.</li>
<li>From the root <code>/bootstrap</code> directory, run <code>npm run docs-serve</code> in the command line.</li>
<li>Open <code>http://localhost:9001</code> in your browser, and voilà.</li>
</ol>
<p>Learn more about using Jekyll by reading its <a href="https://jekyllrb.com/docs/home/" rel="nofollow">documentation</a>.</p>
<h3><a href="#documentation-for-previous-releases" aria-hidden="true" class="anchor" id="user-content-documentation-for-previous-releases"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Documentation for previous releases</h3>
<ul>
<li>For v2.3.2: <a href="https://getbootstrap.com/2.3.2/" rel="nofollow">https://getbootstrap.com/2.3.2/</a></li>
<li>For v3.3.x: <a href="https://getbootstrap.com/docs/3.3/" rel="nofollow">https://getbootstrap.com/docs/3.3/</a></li>
</ul>
<p><a href="https://github.com/twbs/bootstrap/releases">Previous releases</a> and their documentation are also available for download.</p>
<h2><a href="#contributing" aria-hidden="true" class="anchor" id="user-content-contributing"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Contributing</h2>
<p>Please read through our <a href="https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md">contributing guidelines</a>. Included are directions for opening issues, coding standards, and notes on development.</p>
<p>Moreover, if your pull request contains JavaScript patches or features, you must include <a href="https://github.com/twbs/bootstrap/tree/master/js/tests">relevant unit tests</a>. All HTML and CSS should conform to the <a href="https://github.com/mdo/code-guide">Code Guide</a>, maintained by <a href="https://github.com/mdo">Mark Otto</a>.</p>
<p>Editor preferences are available in the <a href="https://github.com/twbs/bootstrap/blob/master/.editorconfig">editor config</a> for easy use in common text editors. Read more and download plugins at <a href="http://editorconfig.org/" rel="nofollow">http://editorconfig.org/</a>.</p>
<h2><a href="#community" aria-hidden="true" class="anchor" id="user-content-community"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Community</h2>
<p>Get updates on Bootstrap's development and chat with the project maintainers and community members.</p>
<ul>
<li>Follow <a href="https://twitter.com/getbootstrap" rel="nofollow">@getbootstrap on Twitter</a>.</li>
<li>Read and subscribe to <a href="https://blog.getbootstrap.com/" rel="nofollow">The Official Bootstrap Blog</a>.</li>
<li>Join <a href="https://bootstrap-slack.herokuapp.com/" rel="nofollow">the official Slack room</a>.</li>
<li>Chat with fellow Bootstrappers in IRC. On the <code>irc.freenode.net</code> server, in the <code>##bootstrap</code> channel.</li>
<li>Implementation help may be found at Stack Overflow (tagged <a href="https://stackoverflow.com/questions/tagged/bootstrap-4" rel="nofollow"><code>bootstrap-4</code></a>).</li>
<li>Developers should use the keyword <code>bootstrap</code> on packages which modify or add to the functionality of Bootstrap when distributing through <a href="https://www.npmjs.com/browse/keyword/bootstrap" rel="nofollow">npm</a> or similar delivery mechanisms for maximum discoverability.</li>
</ul>
<h2><a href="#versioning" aria-hidden="true" class="anchor" id="user-content-versioning"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Versioning</h2>
<p>For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under <a href="http://semver.org/" rel="nofollow">the Semantic Versioning guidelines</a>. Sometimes we screw up, but we'll adhere to those rules whenever possible.</p>
<p>See <a href="https://github.com/twbs/bootstrap/releases">the Releases section of our GitHub project</a> for changelogs for each release version of Bootstrap. Release announcement posts on <a href="https://blog.getbootstrap.com/" rel="nofollow">the official Bootstrap blog</a> contain summaries of the most noteworthy changes made in each release.</p>
<h2><a href="#creators" aria-hidden="true" class="anchor" id="user-content-creators"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Creators</h2>
<p><strong>Mark Otto</strong></p>
<ul>
<li><a href="https://twitter.com/mdo" rel="nofollow">https://twitter.com/mdo</a></li>
<li><a href="https://github.com/mdo">https://github.com/mdo</a></li>
</ul>
<p><strong>Jacob Thornton</strong></p>
<ul>
<li><a href="https://twitter.com/fat" rel="nofollow">https://twitter.com/fat</a></li>
<li><a href="https://github.com/fat">https://github.com/fat</a></li>
</ul>
<h2><a href="#copyright-and-license" aria-hidden="true" class="anchor" id="user-content-copyright-and-license"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Copyright and license</h2>
<p>Code and documentation copyright 2011-2018 the <a href="https://github.com/twbs/bootstrap/graphs/contributors">Bootstrap Authors</a> and <a href="https://twitter.com" rel="nofollow">Twitter, Inc.</a> Code released under the <a href="https://github.com/twbs/bootstrap/blob/master/LICENSE">MIT License</a>. Docs released under <a href="https://github.com/twbs/bootstrap/blob/master/docs/LICENSE">Creative Commons</a>.</p>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>


  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

      
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between py-6 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2018 <span title="0.28117s from unicorn-582790377-lx8vv">GitHub</span>, Inc.</li>
        <li class="mr-3"><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li class="mr-3"><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>

    <a href="https://github.com" aria-label="Homepage" class="footer-octicon" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li class="mr-3"><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li class="mr-3"><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
    You can't perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-ad86efb96de1.js"></script>
    
    <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-53d5033e4efa.js"></script>
    
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>


  </body>
</html>

