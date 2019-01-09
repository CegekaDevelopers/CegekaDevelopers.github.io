---
title: Team

haslink: false
---
<div class="hs_cos_wrapper hs_cos_wrapper_widget hs_cos_wrapper_type_module" id="hs_cos_wrapper_widget_1523272946252" style="" data-hs-cos-type="module" data-hs-cos-general-type="widget">
    <span class="hs_cos_wrapper hs_cos_wrapper_widget hs_cos_wrapper_type_rich_text" id="hs_cos_wrapper_widget_1523272946252_" style="" data-hs-cos-type="rich_text" data-hs-cos-general-type="widget">
        <div class="section-block pb-20">
            <div class="row">
                <div class="column width-9 tmh-perspective">
                    <h2 class="weight-thin font-alt-1 color-charcoal horizon" style="transition:; visibility: visible; opacity: 1; transform: translate3d(0px, 0px, 0px) rotateX(0deg) rotateY(0deg) rotateZ(0deg) scale3d(1, 1, 1); transform-origin: 50% 50% 0px; backface-visibility: hidden;" data-animate-in="preset:slideInUpShort;duration:800ms;">Ons team kent sterke personen.</h2>
                </div>
            </div>
        </div>
    </span>
</div>

<div class="hs_cos_wrapper hs_cos_wrapper_widget hs_cos_wrapper_type_module" id="hs_cos_wrapper_widget_1523274656429" style="" data-hs-cos-type="module" data-hs-cos-general-type="widget">
    <div class="section-block pt-40">
        <div class="row flex boxes full-width">
            {% for member in site.team-members %}
                <div class="solution-columns-home column width-3 member-box">
                    <a class="box xlarge bkg-cegeka-dark-turquoise color-white" href="{{ member.url }}">
                        <p class="lead weight-semi-bold">{{ member.name }}</p>
                        <p>{{ member.position }}</p>
                    </a>
                </div>
            {% endfor %}
        </div>
    </div>
</div>