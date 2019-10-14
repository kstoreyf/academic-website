<h2 id="research">Research</h2>
<div class="row">
{% assign research = site.sections | where_exp: "item" , "item.url contains 'research'"%}
{% for item in site.posts %}
    <div class="6u 12u(narrower)">

        <section class="box special">
            <span class="image featured"><img src="{{ '/images/pic02.jpg' | relative_url }}" alt="" /></span>
            <h3>{{ item.title }}</h3>
            <p>Description here</p>
            <ul class="actions">
                <li><a href="#" class="button alt">Learn More</a></li>
            </ul>
        </section>

    </div>
{% endfor %}
</div>
</section>
