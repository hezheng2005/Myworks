


<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>RepData_PeerAssessment1/PA1_template.md at master · hezheng2005/RepData_PeerAssessment1</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="hezheng2005/RepData_PeerAssessment1" name="twitter:title" /><meta content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research" name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/4664399?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/4664399?v=3&amp;s=400" property="og:image" /><meta content="hezheng2005/RepData_PeerAssessment1" property="og:title" /><meta content="https://github.com/hezheng2005/RepData_PeerAssessment1" property="og:url" /><meta content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/NDY2NDM5OTo3OTEwM2I4MzdjZmY0Y2ZiMzY1NmZmZWEyYjc1Yzg0MDpjMDFlZmI4ZjI4YzQxZjE3MjQzMTM5NjgxZjYzYzA5OGVhYjZhOWVmNGEwNjlmYTQxMzRjNTdkMzgxM2E2MWFh--b37a6c0acc24fb0ee0b2725ad34c7f90e64ffc77">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

        <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="76908525:7354:EC8E99E:558AD620" name="octolytics-dimension-request_id" /><meta content="4664399" name="octolytics-actor-id" /><meta content="hezheng2005" name="octolytics-actor-login" /><meta content="0a0b2b174f7089eace979f8a38c0f9e449791e19ae4d5a322d879ae1282dc51c" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged In">
    <meta name="is-dotcom" content="true">
      <meta name="hostname" content="github.com">
    <meta name="user-login" content="hezheng2005">

      <link rel="icon" sizes="any" mask href="https://assets-cdn.github.com/pinned-octocat.svg">
      <meta name="theme-color" content="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="drasmOB1A7XayIcmSr90jVd9czNx7rsxlX+w8uyRiVam/vpHnKX6wLNmm3Z12ynXIgIia+Q+WL6XBiosckzIrQ==" name="csrf-token" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github/index-fdcc56b9252a5c29d9f914d96ef62f69710f37719a28d3d65b8affe62720a7c4.css" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2/index-c448922147ea2461a83f9e084b9dda6731537d3dc0dec4a245b0bfc0f2aac43e.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="3d09a215e6df343a7b1859fd751fe725">

      
  <meta name="description" content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research">
  <meta name="go-import" content="github.com/hezheng2005/RepData_PeerAssessment1 git https://github.com/hezheng2005/RepData_PeerAssessment1.git">

  <meta content="4664399" name="octolytics-dimension-user_id" /><meta content="hezheng2005" name="octolytics-dimension-user_login" /><meta content="37403100" name="octolytics-dimension-repository_id" /><meta content="hezheng2005/RepData_PeerAssessment1" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="true" name="octolytics-dimension-repository_is_fork" /><meta content="16709733" name="octolytics-dimension-repository_parent_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_parent_nwo" /><meta content="16709733" name="octolytics-dimension-repository_network_root_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/hezheng2005/RepData_PeerAssessment1/commits/master.atom" rel="alternate" title="Recent Commits to RepData_PeerAssessment1:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public fork page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      


        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/hezheng2005/RepData_PeerAssessment1/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/hezheng2005/RepData_PeerAssessment1/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
      </div>

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
            <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:hezheng2005"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-inbox"></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new..."
       data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus left"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="hezheng2005/RepData_PeerAssessment1">This repository</span>
  </div>
    <a class="dropdown-item" href="/hezheng2005/RepData_PeerAssessment1/settings/collaboration" data-ga-click="Header, create new collaborator">
      New collaborator
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-s js-menu-target" href="/hezheng2005"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@hezheng2005" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/4664399?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">hezheng2005</strong>
        </div>
        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/hezheng2005" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>
        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a>

        <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="fRNc6otrhljDSNxKGIgkD4T+I4r3FQVXVxagzEnEp+9sg7N/CjIPwin6Z3iAJCVYXJho/vf8cBh0n3ZCdYw7hA==" /></div>
          <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>

        

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">

        
<ul class="pagehead-actions">

  <li>
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="JCEa9Q4hsahDbZZkvZdzDz4OnfVsp9kRL/2Ez4x9utctXBMCn8PDK9vy+z8KykAXrxGOKwgn0wM1Mq1U/His8A==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="37403100" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/hezheng2005/RepData_PeerAssessment1/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Unwatch
          </span>
        </a>
        <a class="social-count js-social-count" href="/hezheng2005/RepData_PeerAssessment1/watchers">
          1
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
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

    <form accept-charset="UTF-8" action="/hezheng2005/RepData_PeerAssessment1/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="xPJG8PLJ+vjyvsxXEqOleGoZHtr56ueA2+vN2DvIJHLmSBaZuaEsl9jT6BcwdAOweIwiB+L1s+MP689qmEnRqA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar hezheng2005/RepData_PeerAssessment1"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/hezheng2005/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/hezheng2005/RepData_PeerAssessment1/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="096X63YznWy5YrhK5OeKdwvBcWxoqLBZUdjqcCg5TEoNS1CwzIesPIy9Chv9tV8VvmSM4+NV2FFqjP5eD1pgDg==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star hezheng2005/RepData_PeerAssessment1"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/hezheng2005/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>  </div>

  </li>

        <li>
          <form accept-charset="UTF-8" action="/hezheng2005/RepData_PeerAssessment1/fork" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="HZjmBOzLHsTdYWcRmpKSc9clcYaYQJmrSlwKp0cjKCtyj8w7MQMurE2s5Ea4XK8GEV8OHp0x1zXApfHZ/5CMVA==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of hezheng2005/RepData_PeerAssessment1 to your account"
                aria-label="Fork your own copy of hezheng2005/RepData_PeerAssessment1 to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
            <a href="/hezheng2005/RepData_PeerAssessment1/network" class="social-count">15,524</a>
</form>        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo-forked"></span>
          <span class="author"><a href="/hezheng2005" class="url fn" itemprop="url" rel="author"><span itemprop="title">hezheng2005</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/hezheng2005/RepData_PeerAssessment1" data-pjax="#js-repo-pjax-container">RepData_PeerAssessment1</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

            <span class="fork-flag">
              <span class="text">forked from <a href="/rdpeng/RepData_PeerAssessment1">rdpeng/RepData_PeerAssessment1</a></span>
            </span>
        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/hezheng2005/RepData_PeerAssessment1/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/hezheng2005/RepData_PeerAssessment1" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /hezheng2005/RepData_PeerAssessment1">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>


    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/hezheng2005/RepData_PeerAssessment1/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /hezheng2005/RepData_PeerAssessment1/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/hezheng2005/RepData_PeerAssessment1/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /hezheng2005/RepData_PeerAssessment1/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/hezheng2005/RepData_PeerAssessment1/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /hezheng2005/RepData_PeerAssessment1/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/hezheng2005/RepData_PeerAssessment1/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /hezheng2005/RepData_PeerAssessment1/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>
  </ul>


    <div class="sunken-menu-separator"></div>
    <ul class="sunken-menu-group">
      <li class="tooltipped tooltipped-w" aria-label="Settings">
        <a href="/hezheng2005/RepData_PeerAssessment1/settings" aria-label="Settings" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_settings /hezheng2005/RepData_PeerAssessment1/settings">
          <span class="octicon octicon-tools"></span> <span class="full-word">Settings</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
    </ul>
</nav>

              <div class="only-with-full-nav">
                  
<div class="js-clone-url clone-url open"
  data-protocol-type="http">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/hezheng2005/RepData_PeerAssessment1.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="ssh">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:hezheng2005/RepData_PeerAssessment1.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="subversion">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/hezheng2005/RepData_PeerAssessment1" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<div class="clone-options">You can clone with
  <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=http&amp;protocol_type=push" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Qrf8ebuI2Q4qtiu7xJXziyiLm/+znsvb+wB8kXFuWMc7z/HWZN4UFi88QIXEWG7dQPH2UwSCRtBlB4OaWEUEyw==" /></div><button class="btn-link js-clone-selector" data-protocol="http" type="submit">HTTPS</button></form>, <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=push" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="hsUdha3LbNLQ6i6KX4tKi4ujryzMaKfVMt39DBZsjBRdXOFtav+1Fr9goFun3qN7tdsXJedfsQebwAQexVuOog==" /></div><button class="btn-link js-clone-selector" data-protocol="ssh" type="submit">SSH</button></form>, or <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=push" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="SY5nPdiOgj1HRYJIf2iFf721lNJj1p6r3tU11uvYix5Vg+x77XamtvbGsomyCvB5apm73H0J6Hkmu/HqQT9qcg==" /></div><button class="btn-link js-clone-selector" data-protocol="subversion" type="submit">Subversion</button></form>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</div>


  <a href="https://windows.github.com" class="btn btn-sm sidebar-button" title="Save hezheng2005/RepData_PeerAssessment1 to your computer and use it in GitHub Desktop." aria-label="Save hezheng2005/RepData_PeerAssessment1 to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>


                <a href="/hezheng2005/RepData_PeerAssessment1/archive/master.zip"
                   class="btn btn-sm sidebar-button"
                   aria-label="Download the contents of hezheng2005/RepData_PeerAssessment1 as a zip file"
                   title="Download the contents of hezheng2005/RepData_PeerAssessment1 as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/hezheng2005/RepData_PeerAssessment1/blob/1036b39895c4a13f002088cf7bc4402a15bf98c6/PA1_template.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:aa49ae9985544a895c57f0066f0a8a9c -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Find or create a branch…" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Find or create a branch…">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Find or create a branch…" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/hezheng2005/RepData_PeerAssessment1/blob/master/PA1_template.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <form accept-charset="UTF-8" action="/hezheng2005/RepData_PeerAssessment1/branches" class="js-create-branch select-menu-item select-menu-new-item-form js-navigation-item js-new-item-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="18SAjeJWClhQKkrTKbF7ksL7dj1nbk+3Hr439lzIIMYj2F/K2l3gMcgV9hLt60xI5N48rpuav0TUdoMndxa2Qg==" /></div>
            <span class="octicon octicon-git-branch select-menu-item-icon"></span>
            <div class="select-menu-item-text">
              <span class="select-menu-item-heading">Create branch: <span class="js-new-item-name"></span></span>
              <span class="description">from ‘master’</span>
            </div>
            <input type="hidden" name="name" id="name" class="js-new-item-value">
            <input type="hidden" name="branch" id="branch" value="master">
            <input type="hidden" name="path" id="path" value="PA1_template.md">
</form>
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
    <a href="/hezheng2005/RepData_PeerAssessment1/find/master"
          class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/hezheng2005/RepData_PeerAssessment1" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">RepData_PeerAssessment1</span></a></span></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="@hezheng2005" class="avatar" height="24" src="https://avatars3.githubusercontent.com/u/4664399?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/hezheng2005" rel="author">hezheng2005</a></span>
        <time datetime="2015-06-14T19:52:45Z" is="relative-time">Jun 15, 2015</time>
        <div class="commit-title">
            <a href="/hezheng2005/RepData_PeerAssessment1/commit/1036b39895c4a13f002088cf7bc4402a15bf98c6" class="message" data-pjax="true" title="PA1 files">PA1 files</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="@hezheng2005" height="24" src="https://avatars3.githubusercontent.com/u/4664399?v=3&amp;s=48" width="24" />
            <a href="/hezheng2005">hezheng2005</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-actions">

      <div class="btn-group">
        <a href="/hezheng2005/RepData_PeerAssessment1/raw/master/PA1_template.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/hezheng2005/RepData_PeerAssessment1/blame/master/PA1_template.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/hezheng2005/RepData_PeerAssessment1/commits/master/PA1_template.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="https://windows.github.com"
           aria-label="Open this file in GitHub for Windows"
           data-ga-click="Repository, open with desktop, type:windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <form accept-charset="UTF-8" action="/hezheng2005/RepData_PeerAssessment1/edit/master/PA1_template.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="CbtiTdIVrSbuMgzwt5FgJcL5UfLnWFEEqbFNQ6v1UUf0L7w77EYaZMmR/993uyU4Xncv92wz3z9qd/lsqs9x5A==" /></div>
              <button class="octicon-btn tooltipped tooltipped-n" type="submit" aria-label="Edit this file" data-hotkey="e" data-disable-with>
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <form accept-charset="UTF-8" action="/hezheng2005/RepData_PeerAssessment1/delete/master/PA1_template.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="IcxOPwzzeQ5MujbhylEI01QYMBPELCwM86D12MgiVdcpMuK9+tIi/H9tZgKCf8M6Mq5X3uHosY0FYaSnYeHumA==" /></div>
            <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-n" type="submit" aria-label="Delete this file" data-disable-with>
              <span class="octicon octicon-trashcan"></span>
            </button>
</form>    </div>

    <div class="file-info">
        <span class="file-mode" title="File mode">executable file</span>
        <span class="file-info-divider"></span>
        206 lines (155 sloc)
        <span class="file-info-divider"></span>
      4.346 kB
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><table data-table-type="yaml-metadata">
  <thead>
  <tr>
  <th>title</th>

  <th>output</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>Reproducible Research: Peer Assessment 1</div></td>

  <td><div><table>
  <thead>
  <tr>
  <th>html_document</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div><table>
  <thead>
  <tr>
  <th>keep_md</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>true</div></td>
  </tr>
  </tbody>
</table></div></td>
  </tr>
  </tbody>
</table></div></td>
  </tr>
  </tbody>
</table>

<h2><a id="user-content-loading-and-preprocessing-the-data" class="anchor" href="#loading-and-preprocessing-the-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Loading and preprocessing the data</h2>

<div class="highlight highlight-r"><pre><span class="pl-c">#1. Load the data</span>

<span class="pl-smi">data</span> <span class="pl-k">&lt;-</span> read.csv(<span class="pl-s"><span class="pl-pds">"</span>activity.csv<span class="pl-pds">"</span></span>)

<span class="pl-c">#2. Convert the class of the date column from factor to Date.</span>

<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">date</span> <span class="pl-k">&lt;-</span> as.Date(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">date</span>)</pre></div>

<h2><a id="user-content-what-is-mean-total-number-of-steps-taken-per-day" class="anchor" href="#what-is-mean-total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is mean total number of steps taken per day?</h2>

<ol>
<li>Total number of steps taken per day</li>
</ol>

<div class="highlight highlight-r"><pre><span class="pl-smi">ts</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">steps</span><span class="pl-k">~</span><span class="pl-smi">date</span>,<span class="pl-smi">data</span>,<span class="pl-smi">sum</span>)
<span class="pl-smi">ts</span></pre></div>

<pre><code>##          date steps
## 1  2012-10-02   126
## 2  2012-10-03 11352
## 3  2012-10-04 12116
## 4  2012-10-05 13294
## 5  2012-10-06 15420
## 6  2012-10-07 11015
## 7  2012-10-09 12811
## 8  2012-10-10  9900
## 9  2012-10-11 10304
## 10 2012-10-12 17382
## 11 2012-10-13 12426
## 12 2012-10-14 15098
## 13 2012-10-15 10139
## 14 2012-10-16 15084
## 15 2012-10-17 13452
## 16 2012-10-18 10056
## 17 2012-10-19 11829
## 18 2012-10-20 10395
## 19 2012-10-21  8821
## 20 2012-10-22 13460
## 21 2012-10-23  8918
## 22 2012-10-24  8355
## 23 2012-10-25  2492
## 24 2012-10-26  6778
## 25 2012-10-27 10119
## 26 2012-10-28 11458
## 27 2012-10-29  5018
## 28 2012-10-30  9819
## 29 2012-10-31 15414
## 30 2012-11-02 10600
## 31 2012-11-03 10571
## 32 2012-11-05 10439
## 33 2012-11-06  8334
## 34 2012-11-07 12883
## 35 2012-11-08  3219
## 36 2012-11-11 12608
## 37 2012-11-12 10765
## 38 2012-11-13  7336
## 39 2012-11-15    41
## 40 2012-11-16  5441
## 41 2012-11-17 14339
## 42 2012-11-18 15110
## 43 2012-11-19  8841
## 44 2012-11-20  4472
## 45 2012-11-21 12787
## 46 2012-11-22 20427
## 47 2012-11-23 21194
## 48 2012-11-24 14478
## 49 2012-11-25 11834
## 50 2012-11-26 11162
## 51 2012-11-27 13646
## 52 2012-11-28 10183
## 53 2012-11-29  7047
</code></pre>

<ol>
<li>Histogram of the total number of steps taken each day</li>
</ol>

<div class="highlight highlight-r"><pre>par(<span class="pl-v">mar</span><span class="pl-k">=</span>c(<span class="pl-c1">5</span>, <span class="pl-c1">4</span>, <span class="pl-c1">4</span>, <span class="pl-c1">2</span>) <span class="pl-k">+</span> <span class="pl-c1">0.1</span>)
hist(<span class="pl-smi">ts</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Total Number of Steps Taken Each Day<span class="pl-pds">"</span></span>,<span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Number of Steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/hezheng2005/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-3-1.png" target="_blank"><img src="/hezheng2005/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-3-1.png" alt="plot of chunk unnamed-chunk-3" style="max-width:100%;"></a> </p>

<ol>
<li>The mean and median of the total number of steps taken per day</li>
</ol>

<div class="highlight highlight-r"><pre>mean(<span class="pl-smi">ts</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)</pre></div>

<pre><code>## [1] 10766.19
</code></pre>

<div class="highlight highlight-r"><pre>median(<span class="pl-smi">ts</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)</pre></div>

<pre><code>## [1] 10765
</code></pre>

<h2><a id="user-content-what-is-the-average-daily-activity-pattern" class="anchor" href="#what-is-the-average-daily-activity-pattern" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is the average daily activity pattern?</h2>

<div class="highlight highlight-r"><pre><span class="pl-smi">as</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">steps</span><span class="pl-k">~</span><span class="pl-smi">interval</span>,<span class="pl-smi">data</span>,<span class="pl-smi">mean</span>)
plot(<span class="pl-smi">as</span><span class="pl-k">$</span><span class="pl-smi">interval</span>,<span class="pl-smi">as</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-v">type</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>,<span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Average Number of Steps Taken for Each Interval<span class="pl-pds">"</span></span>,<span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>5-minute Interval<span class="pl-pds">"</span></span>,<span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Average Number of Steps Taken<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/hezheng2005/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-5-1.png" target="_blank"><img src="/hezheng2005/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-5-1.png" alt="plot of chunk unnamed-chunk-5" style="max-width:100%;"></a> </p>

<div class="highlight highlight-r"><pre><span class="pl-smi">maxsteps</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">as</span><span class="pl-k">$</span><span class="pl-smi">interval</span>[which(<span class="pl-smi">as</span><span class="pl-k">$</span><span class="pl-smi">steps</span><span class="pl-k">==</span>max(<span class="pl-smi">as</span><span class="pl-k">$</span><span class="pl-smi">steps</span>))]</pre></div>

<p>The No. 835 interval contains the maxium number of steps.</p>

<h2><a id="user-content-imputing-missing-values" class="anchor" href="#imputing-missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Imputing missing values</h2>

<p>The total number of missing values in the dataset is</p>

<div class="highlight highlight-r"><pre>sum(is.na(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>))</pre></div>

<pre><code>## [1] 2304
</code></pre>

<p>Use the mean for the 5-minute interval to fill in all of the missing values</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">newdata</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">data</span>
<span class="pl-k">for</span> (<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span>nrow(<span class="pl-smi">newdata</span>)) <span class="pl-k">if</span>(is.na(<span class="pl-smi">newdata</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[<span class="pl-smi">i</span>]))<span class="pl-smi">newdata</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[<span class="pl-smi">i</span>] <span class="pl-k">&lt;-</span> <span class="pl-smi">as</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[which(<span class="pl-smi">newdata</span><span class="pl-k">$</span><span class="pl-smi">interval</span>[<span class="pl-smi">i</span>]<span class="pl-k">==</span><span class="pl-smi">as</span><span class="pl-k">$</span><span class="pl-smi">interval</span>)]</pre></div>

<p>Make a histogram of the total number of steps taken each day</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">ts2</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">steps</span><span class="pl-k">~</span><span class="pl-smi">date</span>,<span class="pl-smi">newdata</span>,<span class="pl-smi">sum</span>)
hist(<span class="pl-smi">ts2</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Total Number of Steps Taken Each Day After filling in all NAs<span class="pl-pds">"</span></span>,<span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Number of Steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/hezheng2005/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-8-1.png" target="_blank"><img src="/hezheng2005/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-8-1.png" alt="plot of chunk unnamed-chunk-8" style="max-width:100%;"></a> </p>

<p>The mean and median total number of steps taken per day</p>

<div class="highlight highlight-r"><pre><span class="pl-c"># The mean</span>
mean(<span class="pl-smi">ts2</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)</pre></div>

<pre><code>## [1] 10766.19
</code></pre>

<div class="highlight highlight-r"><pre><span class="pl-c"># The median</span>
median(<span class="pl-smi">ts2</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)</pre></div>

<pre><code>## [1] 10766.19
</code></pre>

<p>The mean doesn't change becuase I filled in means for each 5-minute interval. However, the median changed a bit, from 10765 to 10766.19.</p>

<h2><a id="user-content-are-there-differences-in-activity-patterns-between-weekdays-and-weekends" class="anchor" href="#are-there-differences-in-activity-patterns-between-weekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>Are there differences in activity patterns between weekdays and weekends?</h2>

<div class="highlight highlight-r"><pre><span class="pl-c"># Weekday or weekend</span>
library(<span class="pl-smi">chron</span>)
library(<span class="pl-smi">plyr</span>)
<span class="pl-smi">newdata</span> <span class="pl-k">&lt;-</span> mutate(<span class="pl-smi">newdata</span>,<span class="pl-v">day</span><span class="pl-k">=</span>is.weekend(<span class="pl-smi">date</span>))
<span class="pl-k">for</span> (<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span>nrow(<span class="pl-smi">newdata</span>)) <span class="pl-k">if</span>(<span class="pl-smi">newdata</span><span class="pl-k">$</span><span class="pl-smi">day</span>[<span class="pl-smi">i</span>]) <span class="pl-smi">newdata</span><span class="pl-k">$</span><span class="pl-smi">day</span>[<span class="pl-smi">i</span>] <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>weekend<span class="pl-pds">"</span></span> <span class="pl-k">else</span> <span class="pl-smi">newdata</span><span class="pl-k">$</span><span class="pl-smi">day</span>[<span class="pl-smi">i</span>] <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>
<span class="pl-k">invisible</span>(as.factor(<span class="pl-smi">newdata</span><span class="pl-k">$</span><span class="pl-smi">day</span>))

<span class="pl-c"># Make a panel plot</span>
library(<span class="pl-smi">lattice</span>)
<span class="pl-smi">mstep</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">newdata</span><span class="pl-k">$</span><span class="pl-smi">steps</span>,<span class="pl-v">by</span><span class="pl-k">=</span><span class="pl-k">list</span>(<span class="pl-smi">newdata</span><span class="pl-k">$</span><span class="pl-smi">interval</span>,<span class="pl-smi">newdata</span><span class="pl-k">$</span><span class="pl-smi">day</span>),<span class="pl-smi">mean</span>)
names(<span class="pl-smi">mstep</span>) <span class="pl-k">&lt;-</span> c(<span class="pl-s"><span class="pl-pds">"</span>interval<span class="pl-pds">"</span></span>,<span class="pl-s"><span class="pl-pds">"</span>day<span class="pl-pds">"</span></span>,<span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span>)
xyplot(<span class="pl-smi">steps</span><span class="pl-k">~</span><span class="pl-smi">interval</span> <span class="pl-k">|</span> <span class="pl-smi">day</span>, <span class="pl-smi">mstep</span>,<span class="pl-v">type</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>,<span class="pl-v">layout</span><span class="pl-k">=</span>c(<span class="pl-c1">1</span>,<span class="pl-c1">2</span>),<span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Interval<span class="pl-pds">"</span></span>,<span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Number of steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/hezheng2005/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-10-1.png" target="_blank"><img src="/hezheng2005/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-10-1.png" alt="plot of chunk unnamed-chunk-10" style="max-width:100%;"></a> </p>

<p>Activity patterns differ between weekdays and weekends. During weekends, people walk more in the whole day. However, during weekdays, people walk more in the morning.</p>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
      <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.05236s from github-fe140-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-808fcfcd63c9ecba3e84453f540cb1cbafde48c6b30c1d51ebd4e67e88ff66bd.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github/index-d235b6c3e48ba9782d3a995ac5332f39a20f29dbe928d28495d7299b2b32c25b.js"></script>
      
      
  </body>
</html>

