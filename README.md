Social buttons links
==============

All social buttons links

Sharing links
============

## Supported Social Networks

* [Blogger](#blogger)
* [Buffer](#buffer)
* [Delicious](#delicious)
* [Digg](#digg)
* [Evernote](#evernote)
* [Facebook](#facebook)
* [Google Bookmarks](#google-bookmarks)
* [Google+](#google-plus)
* [Linked In](#linkedin)
* [Mailru](#mailru)
* [Myspace](#myspace)
* [Odnoklassniki](#odnoklassniki)
* [Pinterest](#pinterest)
* [Reddit](#reddit)
* [StumbleUpon](#stumbleupon)
* [Tumblr](#tumblr)
* [Twitter](#twitter)
* [VK](#vk)
* [Xing Share](#xing-share)

### Blogger

```
https://www.blogger.com/blog-this.g?u={url}&n={title}&t={content}
```

##### URL Arguments

Argument | Description
--- | --- 
{url} | The url you want to share (**encoded**) 
{title} | The page title of the url you want to share 
{content} | A longer description of the content you are sharing

### Buffer

```
http://bufferapp.com/add?text={title}&url={url}
```

##### URL Arguments

Argument | Description
--- | ---
{url} | The url you want to share (**encoded**)
{title} | The page title of the url you want to share

### Delicious

```
https://delicious.com/save?v=5&provider={provider}&noui&jump=close&url={url}&title={title}
```
##### URL Arguments

Argument | Description 
--- | --- 
{url} | The url you want to share (**encoded**)
{title} | The page title of the url you want to share
{provider} | Company who is sharing the url


### Digg

```
http://digg.com/submit?url={url}&title={title}
```

##### URL Arguments

Argument | Description 
--- | ---
{url} | The url you want to share (**encoded**)
{title} | The page title of the url you want to share 

### Evernote

```
http://www.evernote.com/clip.action?url={url}title={title}
```
##### URL Arguments

Argument | Description 
--- | ---
{url} | The url you want to share (**encoded**) 
{title} | The page title of the url you want to share 

### Facebook

```
http://www.facebook.com/sharer.php?u={url}
```

##### URL Arguments

Argument | Description 
--- | ---
{url} | The url you want to share (**encoded**) 

#### Share Dialog:

```
https://www.facebook.com/dialog/share?app_id={app_id}&display=page&href={url}&redirect_uri={redirect_url}
```

##### URL Arguments

Argument | Description 
--- | --- 
{href} | The url you want to share (**encoded**) 
{app_id} | The App ID 
{redirect_url} | The url a sharer will be redirected to after a successful share | Facebook


### Google Bookmarks

```
http://www.google.com/bookmarks/mark?op=edit&bkmk={url}&title={title}&annotation={content}
```

##### URL Arguments

Argument | Description 
--- | --- 
{url} | The url you want to share (**encoded**)
{title} | The page title of the url you want to share
{content} | A longer description of the content you are sharing

### Google+

```
https://plus.google.com/share?url={url}
```

###### URL Arguments

Argument | Description 
--- | --- 
{url} | The url you want to share (**encoded**) 

### Linked In

```
http://www.linkedin.com/shareArticle?url={url}&title={title}
```

##### URL Arguments

Argument | Description 
--- | ---
{url} | The url you want to share (**encoded**)
{title} | The page title of the url you want to share 

### Mailru

```
http://connect.mail.ru/share?url={url}&title={title}&description={content}&imageurl={image}
```

##### URL Arguments

Argument | Description
--- | ---
{url} | The url you want to share (**encoded**)
{title} | The page title of the url you want to share 
{content} | A longer description of the content you are sharing 
{image} | The image/thumbnail to use when sharing

### Myspace

```
http://www.myspace.com/Modules/PostTo/Pages/?t={title}&c={content}&u={url}&l={level}
```

##### URL Arguments

Argument | Description 
--- | ---
{title} | The page title of the url you want to share
{content} | A longer description of the content you are sharing 
{url} | The url you want to share (**encoded**)
{level} | Level(default 3)

### Odnoklassniki

```
http://www.odnoklassniki.ru/dk?st.cmd=addShare&st.s=1&st.comments={content}&st._surl={url}
```

##### URL Arguments

Argument | Description 
--- | --- 
{url} | The url you want to share (**encoded**) 
{content} | A longer description of the content you are sharing

### Pinterest

```
https://pinterest.com/pin/create/bookmarklet/?url={url}&media={image}&is_video={is_video}&description={title}
```

##### URL Arguments

Argument | Description 
--- | --- 
{url} | The url you want to share (**encoded**) 
{image} | The image/thumbnail to use when sharing
{is_video} | If the content is a video or not 
{title} | The page title of the url you want to share | Most

### Reddit

```
http://reddit.com/submit?url={url}&title={title}
```

##### URL Arguments

Argument | Description
--- | --- 
{url} | The url you want to share (**encoded**)
{title} | The page title of the url you want to share 

### StumbleUpon

```
http://www.stumbleupon.com/submit?url={url}&title={title}
```

##### URL Arguments

Argument | Description 
--- | --- 
{url} | The url you want to share (**encoded**) 
{title} | The page title of the url you want to share 

### Tumblr

```
https://www.blogger.com/blog-this.g?u={url}&n={title}&t={content}
```

##### URL Arguments

Argument | Description 
--- | --- 
{url} | The url you want to share (**encoded**)
{title} | The page title of the url you want to share
{content} | A longer description of the content you are sharing 

### Twitter

```
http://www.tumblr.com/share/link?url={url}&name={title}&description={description}&via{via}&hastags={hashtags}
```

##### URL Arguments

Argument | Description
--- | ---
{url} | The url you want to share (**encoded**)
{title} | The page title of the url you want to share 
{via} | optional Twitter username of content author (don't include "@") 
{hashtags} | optional Hashtags appended onto the tweet (comma separated. don't include "#") 

### VK

```
https://vk.com/share.php?url={url}&title={title}&description={content}&image={image}&noparse={parse}
```

##### URL Arguments

Argument | Description 
--- | --- 
{url} | The url you want to share (**encoded**)
{title} | The page title of the url you want to share 
{content} | A longer description of the content you are sharing 
{image} | The image/thumbnail to use when sharing 
{parse} | Parse url? (0 or 1, default 1) 

### Xing Share

```
https://www.xing-share.com/app/user?op=share;sc_p=xing-share;url={url}
```

##### URL Arguments

Argument | Description
--- | ---
{url} | The url you want to share (**encoded**) 
