Generic Prices
================

<h2>Version</h2>
version 0.1.2

<h2>Documentation</h2>

<h6>Require files:</h6>
[prices.less](https://github.com/balmor/generic-prices/blob/master/less/prices.less) - base file for magento, should be in (skin\frontend\base\default\css\catalog) - don't change this file <br>
[vars-prices.less](https://github.com/balmor/generic-prices/blob/master/less/vars-prices.less) - and the local file variables

Default Magento Generic Prices HTML for <b>Regular Price</b> - we can't change this html:
```html
    <div class="price-box" itemtype="http://data-vocabulary.org/Offer" itemscope="" itemprop="offerDetails">
        <meta itemprop="currency" content="USD">
        <span class="regular-price">
            <span class="price">19.90 &euro;</span>
        </span>
    </div>
```

and for <b>Discount, Old & Special prices</b>:
```html
    <div class="price-box" itemtype="http://data-vocabulary.org/Offer" itemscope="" itemprop="offerDetails">
        <span class="discount">-6%</span>
        <meta itemprop="currency" content="EUR">                  
        <p class="old-price">
            <span class="price-label">Prix normal :</span>
            <span class="price">15,90 &euro;</span>
        </p>

        <p class="special-price">
            <span class="price-label">Prix spécial :</span>
            <span class="price" itemprop="price">14,99 &euro;</span>
        </p>            
    </div> 
```


<h2>How it works</h2>
You can see exmaple page <a href="http://generic.balmor.eu/prices/">here</a>.