# twitter-homepage
<!DOCTYPE html>
<html>
  <head>
    <title>Twitter</title>
    <link rel="stylesheet" href="css/global.css" />
    <link rel="stylesheet" href="css/blocks/layout.css" />
    <link rel="stylesheet" href="css/blocks/brand.css" />
    <link rel="stylesheet" href="css/blocks/sidebar-menu.css" />
    <link rel="stylesheet" href="css/blocks/tweet.css" />
    <link rel="stylesheet" href="css/blocks/trends-for-you.css" />
    <link rel="stylesheet" href="css/blocks/who-to-follow.css" />
    <link rel="stylesheet" href="style.css">
    <script src="https://code.iconify.design/2/2.2.1/iconify.min.js"></script>


    <div class="layout">
      <div class="layout__left-sidebar">
        <img src="./svg/twitter.svg" class="brand" />
        <div class="sidebar-menu">
          <div class="sidebar-menu__item sidebar-menu__item--active">
            <img src="./svg/home.svg" class="sidebar-menu__item-icon" />
            Home
          </div>
          <div class="sidebar-menu__item">
            <img src="./svg/explore.svg" class="sidebar-menu__item-icon" />
            Explore
          </div>

          <div class="sidebar-menu__item">
            <img
              src="./svg/notifications.svg"
              class="sidebar-menu__item-icon"
            />
            Notifications
          </div>

          <div class="sidebar-menu__item">
            <img src="./svg/messages.svg" class="sidebar-menu__item-icon" />
            Messages
          </div>

          <div class="sidebar-menu__item">
            <img src="./svg/profile.svg" class="sidebar-menu__item-icon" />
            Profile
          </div>

          <div class="sidebar-menu__item">
            <img src="./svg/more.svg" class="sidebar-menu__item-icon" />
            More
          </div>
          <button class="sidebar__tweet">Tweet</button>

        </div>
      </div>
      <div class="layout__main">
    <!--feed starts-->
    <div class="feed">
        <div class="feed__header">
            <h2>Home 

            </h2>
            
        </div>

        <!--tweetbox starts-->
        <div class="tweetBox">
            <form>
                <div class="tweetbox__input">
                    <img 
                    src="https://cdn-icons-png.flaticon.com/512/417/417777.png"
                    alt=""
                />
                <input type="text" placeholder="What's Happening?">
                </div>
                
                <button class="tweetBox__tweetButton">Tweet</button>
            
              </form>
        </div>
        <!-- tweetbox ends-->

    </div>
    <!--feed ends-->
        <div class="tweet">
          <img class="tweet__author-logo" src="./images/flower3.jpg" />
          <div class="tweet__main">
            <div class="tweet__header">
              <div class="tweet__author-name">
                Prasa
              </div>
              <div class="tweet__author-slug">
                @prasa
              </div>
              <div class="tweet__publish-time">
                14m
              </div>
            </div>
            <div class="tweet__content">
              Happy Canada Day!
              <img class="tweet__image" src="./images/flag.jpg" />

            <div class="post__footer">
              <span class="iconify" data-icon="system-uicons:speech-bubble"></span>
              <span class="iconify" data-icon="carbon:repeat"></span>
              <span class="iconify" data-icon="akar-icons:heart"></span>
              <span class="iconify" data-icon="akar-icons:share-box"></span>
            </div>

            </div>
          </div>
        </div>
        <div class="tweet">
          <img class="tweet__author-logo" src="./images/uber.jpg" />
          <div class="tweet__main">
            <div class="tweet__header">
              <div class="tweet__author-name">
                Uber
              </div>
              <div class="tweet__author-slug">
                @Uber
              </div>
              <div class="tweet__publish-time">
                2h
              </div>
            </div>
            <div class="tweet__content">
              Go with ease ➡️ Go with friends ➡️ Go with confidence ➡️ Go anywhere ➡️
              Hop in ➡️ 
              <a href=""
                >http://Uber.com</a
              >
              <div class="post__footer">
                <span class="iconify" data-icon="system-uicons:speech-bubble"></span>
                <span class="iconify" data-icon="carbon:repeat"></span>
                <span class="iconify" data-icon="akar-icons:heart"></span>
                <span class="iconify" data-icon="akar-icons:share-box"></span>
              </div>
            </div>
          </div>
        </div>

        <div class="tweet">
          <img class="tweet__author-logo" src="./images/vangogh.jpg" />
          <div class="tweet__main">
            <div class="tweet__header">
              <div class="tweet__author-name">
                Vincent Van Gogh
              </div>
              <div class="tweet__author-slug">
                @TheRealVanGogh
              </div>
              <div class="tweet__publish-time">
                5h
              </div>
            </div>
            <div class="tweet__content">
              Orchard in Blossom, 1888
              <a href="https://typeclasses.com/typed-holes"
                ></a
              >
              <img class="tweet__image" src="./images/vpainting1.jpg" />
              <div class="post__footer">
                <span class="iconify" data-icon="system-uicons:speech-bubble"></span>
                <span class="iconify" data-icon="carbon:repeat"></span>
                <span class="iconify" data-icon="akar-icons:heart"></span>
                <span class="iconify" data-icon="akar-icons:share-box"></span>
              </div>
            </div>
          </div>
        </div>

        <div class="tweet">
          <img class="tweet__author-logo" src="./images/uniceflogo.jpg" />
          <div class="tweet__main">
            <div class="tweet__header">
              <div class="tweet__author-name">
                UNICEF
              </div>
              <div class="tweet__author-slug">
                @UNICEF
              </div>
              <div class="tweet__publish-time">
                15h
              </div>
            </div>
            <div class="tweet__content">
            Imagine if every sentence looked like this to you. That is the reality of 471 million primary school-aged children who are unable to read and understand a simple text.
            World leaders need to take action now.
                                                                                   
                <img class="tweet__image" src="./images/unicef_post.jpg" />
                <div class="post__footer">
                  <span class="iconify" data-icon="system-uicons:speech-bubble"></span>
                  <span class="iconify" data-icon="carbon:repeat"></span>
                  <span class="iconify" data-icon="akar-icons:heart"></span>
                  <span class="iconify" data-icon="akar-icons:share-box"></span>
                </div>
              </div>
          </div>
        </div>

        <div class="tweet">
          <img class="tweet__author-logo" src="./images/profilepic.jpg" />
          <div class="tweet__main">
            <div class="tweet__header">
              <div class="tweet__author-name">
                Mood Photos
              </div>
              <div class="tweet__author-slug">
                @moodyphotos
              </div>
              <div class="tweet__publish-time">
                1d
              </div>
            </div>
            <div class="tweet__content">
              Pic credit: SXMBA
              <img class="tweet__image" src="./images/torontopic.jpg" />
              <div class="post__footer">
                <span class="iconify" data-icon="system-uicons:speech-bubble"></span>
                <span class="iconify" data-icon="carbon:repeat"></span>
                <span class="iconify" data-icon="akar-icons:heart"></span>
                <span class="iconify" data-icon="akar-icons:share-box"></span>
              </div>
            </div>
          </div>
        </div>

        <div class="tweet">
          <img class="tweet__author-logo" src="./images/filmicon.jpg" />
          <div class="tweet__main">
            <div class="tweet__header">
              <div class="tweet__author-name">
                Princess Cinemas
              </div>
              <div class="tweet__author-slug">
                @PrincessCinemasKW
              </div>
              <div class="tweet__publish-time">
                3d
              </div>
            </div>
            <div class="tweet__content">
              Coming to Toronto near YOU!
              <img class="tweet__image" src="./images/movieposter.jpg" />
              <div class="post__footer">
                <span class="iconify" data-icon="system-uicons:speech-bubble"></span>
                <span class="iconify" data-icon="carbon:repeat"></span>
                <span class="iconify" data-icon="akar-icons:heart"></span>
                <span class="iconify" data-icon="akar-icons:share-box"></span>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="layout__right-sidebar-container">
        <div class="layout__right-sidebar">
          <div class="trends-for-you">
            <div class="trends-for-you__block">
              <div class="trends-for-you__heading">
                Trends for you
              </div>
            </div>
            <div class="trends-for-you__block">
              <div class="trends-for-you__meta-information">
                Trending in Canada
              </div>
              <div class="trends-for-you__trend-name">
                #Metaverse
              </div>
              <div class="trends-for-you__meta-information">
                230k Tweets
              </div>
            </div>
            <div class="trends-for-you__block">
              <div class="trends-for-you__meta-information">
                Trending in Brazil
              </div>
              <div class="trends-for-you__trend-name">
                #COVID-19
              </div>
            </div>
            <div class="trends-for-you__block">
              <div class="trends-for-you__meta-information">
                News ·  Trending
              </div>
              <div class="trends-for-you__trend-name">
                #PrideMonth
              </div>
              <div class="trends-for-you__meta-information">
                5,400 Tweets
              </div>
            </div>
          </div>
          <div class="who-to-follow">
            <div class="who-to-follow__block">
              <div class="who-to-follow__heading">
                Who to follow
              </div>
            </div>
            <div class="who-to-follow__block">
              <img
                class="who-to-follow__author-logo"
                src="./images/coldplay.jpg"
              />
              <div class="who-to-follow__content">
                <div>
                  <div class="who-to-follow__author-name">
                    Coldplay
                  </div>
                  <div class="who-to-follow__author-slug">
                    @coldplay
                  </div>
                </div>
                <div class="who-to-follow__button">
                  Follow
                </div>
              </div>
            </div>
            <div class="who-to-follow__block">
              <img
                class="who-to-follow__author-logo"
                src="./images/aoc.jpg"
              />
              <div class="who-to-follow__content">
                <div>
                  <div class="who-to-follow__author-name">
                    Alexandria Ocasio-Cortez
                  </div>
                  <div class="who-to-follow__author-slug">
                    @AOC
                  </div>
                </div>
                <div class="who-to-follow__button">
                  Follow
                </div>
              </div>
            </div>

            <div class="who-to-follow__block">
              <img
                class="who-to-follow__author-logo"
                src="./images/uoft.jpg"
              />
              <div class="who-to-follow__content">
                <div>
                  <div class="who-to-follow__author-name">
                    University of Toronto

                  </div>
                  <div class="who-to-follow__author-slug">
                    @UofT
                  </div>
                </div>
                <div class="who-to-follow__button">
                  Follow
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
