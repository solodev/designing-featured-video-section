# designing-featured-video-section
With the popularity of video content skyrocketing, properly featuring your videos can boost your website's engagement. Here's how to design a featured video section for your website.
Over the last decade, digital marketing's focus on video content has skyrocketed.
YouTube videos are being consumed at rates never before seen in the company's history, and 45 percent of people watch more than an hour of Facebook or YouTube videos each week. 

## Tutorial		  
For detailed instruction's, view Solodev's [Designing a Featured Video Section for Your Website](https://www.solodev.com/blog/designing-a-featured-video-section-for-your-website.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](http://jsfiddle.net/solodev/9bwtk7Ln/).

## HTML

The tutorial contains the following basic HTML markup.

```
<section class="video bg-light py-3" aria-label="Video Section">
  <h2 class="font-weight-bold text-uppercase text-center my-3">Solodev Featured videos</h2>
	<div class="container">
		<div class="row d-md-flex">
			<div class="col-md-6 flex-md-column">
				<div class="embed-responsive embed-responsive-16by9">
					<iframe width="560" height="315" src="https://www.youtube.com/embed/qN3OueBm9F4?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
				</div>
			</div>

			<div class="col-md-3 my-3 my-md-0 flex-md-column">
				<div class="watch-video h-100 bg-white p-3">
					<h4><a href="https://youtu.be/MO7Rek2Rf_0"><strong>Marketing Tips</strong></a></h4>
					<p class="video-data">Published on May 15, 2018</p>
					<div class="embed-responsive embed-responsive-16by9">
						<iframe width="560" height="315" src="https://www.youtube.com/embed/MO7Rek2Rf_0?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
					</div>
					<p class="pt-3"><small><a aria-label="Watch Video 2" href="https://youtu.be/MO7Rek2Rf_0" target="_blank">Watch Video</a></small></p>
				</div>
			</div>

			<div class="col-md-3 flex-md-column">
				<div class="watch-video h-100 bg-white p-3">
					<h4><a href="https://www.youtube.com/watch?v=sWkUyxp3ap0"><strong>CMS Featutres</strong></a></h4>
					<p class="video-data">Published on April 11, 2018</p>
					<div class="embed-responsive embed-responsive-16by9">
						<iframe width="560" height="315" src="https://www.youtube.com/embed/5Fbb7RWQsPo?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
					</div>
					<p class="pt-3"><small><a aria-label="Watch Video 2" href="https://www.youtube.com/watch?v=5Fbb7RWQsPo" target="_blank">Watch Video</a></small></p>			
				</div>
			</div>

		</div>
		<p class="text-right mt-5">
			<a href="https://www.youtube.com/channel/UC052Wqq-4KeX5F4bC1kXzdQ" target="_blank" class="link-all text-uppercase">See more videos <i class="fa fa-caret-right" aria-hidden="true"></i></a>
		</p>
  </div>
</section>            
```

## CSS

All required CSS is contained with style.css

## External Resources

This tutorial includes the following third party resources.

```
<link href="http://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" rel="stylesheet">
<script src="http://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
<script src="http://stackpath.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js"></script>
```


