---
layout: items
---

{% include head.html %}

<div class="content">
<h1>Welcome To Our Shop</h1><br/>
<h2>Featured Products</h2>
</div>


<!-------- products --------------->

    {% for itemslot in furniture.itemslots %}
	    <div class="col-lg-4 col-sm-6">
            <a href="{{furniture.page-link}}" class="portfolio-box">
                    <img src="{{furniture.image1}}" class="img-responsive" alt="{{furniture.description}}">
                    <div class="portfolio-box-caption">
                        <div class="portfolio-box-caption-content">
                            <div class="project-name">
                                {{furniture.name}}
                            </div>
                        </div>
                    </div>
                </a>
        </div>
    {% endfor %}



