---
layout: post
title: "Solend pools"
client:  "Solend"
field: "Crypto / fintech"
role: "Product design"
duration: "4 months"
imglink: "assets/img/solend.jpg"
heroImglink: "/assets/img/solendHero.jpg"
date:   2022-04-08 -0700
location:   "Oakland, CA"
author:   "Yishan"
description_short: "Designing Solend isolated pool"
description_long: "Solend is a decentralized lending and borrowing protocol on Solana. I designed and helped them implement pool feature to help users better navigate through different assets."
nextCase: "https://www.yishanzhang.com/2022/04/08/train.html"
---

<div class="side-title"> 00.  BACKGROUND </div>

### Solend is a fast-growing decentralized lending platform with a total supply of $1.26B since first established in 2021. 

The number of available assets to trade on the platform is growing fast. The current website has all the assets displayed as one list, but the fast-growing number of assets added to the platform regularly made it hard for users to find and navigate through the list of assets.

<figure>
    <img src="/assets/img/solendCase01.jpg">
</figure>

<div class="side-title"> 01.  GOALS </div>


### Design and implement pool feature to the current website

1. Maintain the current website information architecture
2. Display pools available to trade clearly
3. Shows information of assets in each pool
4. Design for future growth - easy to add more pools and assets to the website.


<div class="side-title"> 02.  ITERATIONS </div>

### Option 1 - Seperate Pool Page

I added a pool button to the top navigation bar for the first option, and the pool features became their separate page. Once users click on the button, they will be led to an individual pool page with an overview of the pool and a  list of different assets in that pool.

<figure>
    <img src="/assets/img/solendCase02.jpg">
</figure>

#### What’s working? 

This option uses space efficiently. The added pool feature won't take up more space on the page, and more assets can be displayed at once. It also automatically leads the user to the pool Solend wants to promote.

#### What’s not working? 

Adding more pools to the website can be challenging. This option works well for a few pools, and if the platform further expands and has more pools added, there won't be enough space in the top navigation bar to display all the pools, and users might have a hard time finding the pool they want to access.


#### Conclusion 
Even though this option uses space efficiently and works well for currently available pools, it is difficult for the company to add more pools in the future, which seems to be a significant constraint.

Since the company is growing fast, one of the goals I'm trying to accomplish is to make sure my design fits with its projected growth and make it easier for them to add more pools in the future if needed.


### Option 2 - Drop Down Menu
The page automatically leads the user to the default Solend pool for this option. A drop-down menu on the default pool button lists all the other pools and basic information about each pool.

<figure>
    <img src="/assets/img/solendCase03.jpg">
</figure>

#### What’s working? 

It contains more information about each pool. Users will see more statistics of each pool when they click on the drop-down menu. It also uses space efficiently, allowing users to see more assets at once. 

#### What’s not working? 

Users only see one pool unless they use the drop-down menu. Once click on the drop-down menu, it also blocks a significant portion of the page, especially if more pools are added to the website in the future. 


#### Conclusion 

Even though this option shows users more information on each pool, I don't particularly like it since the drop-down menu can become quite bulky if there are multiple pools. And also, the fact that it doesn't show all pools available can be confusing since users might not realize there are pools besides the default Solend pool.

I don't think this is the strongest option for those two reasons. 

### Option 3 - Pool Tab

I kept the navigation bar and market overview for this option and added different pool tabs underneath them. Users can switch between different tabs to access various tools, and they will also see the statistic of each pool. When users hover over the tab, it will also show information, including the pool's assets and the overall supply and borrow.

<figure>
    <img src="/assets/img/solendCase04.jpg">
</figure>

#### What’s working?  

Allows users to see all the pools. They can easily switch between different pools. It can also accommodate any future pools Solend might want to add. Users can also have an overview of the pool when hovering.

#### What’s not working? 

This option uses up more space at the top. The page will display fewer assets. 

#### Conclusion 

It maintains the basic architecture of the website without the need to make significant changes. It can also satisfy the company's future growth needs since one of the benefits of this option is how easily it can add more pools to the tab. It also has the benefits of the above two options - it allows users to see all the pools available clearly and readily switch between different pools and shows some basic statistics of each pool.

The only drawback of this option is that it doesn't use the space on the top of the page efficiently. For the next step, I want to explore ways to lay out the elements, so the pool tabs don't take up too much unnecessary space.


<div class="side-title"> 03. DESIGN </div>

### All pools page

While talking to the team, we realized the need to have an additional page that lists all the pools available before users get into the pool tabs. This will be helpful as Solend grows and adds more pools. Users can see all the pools with key stats before getting into the pool.

<figure>
    <img src="/assets/img/solendCase05.jpg">
</figure>


### Market stats

This page lists all the markets within each pool, and users can easily switch between different pools using the pool tab. Users will also see more stats on the market when they hover over.

<figure>
    <img src="/assets/img/solendCase06.jpg">
</figure>

<div class="side-title"> 04.  IMPACT </div>

### The total assets supplied increased more than 40% after the redesign.

After the redesign, the total assets grew from $800M to $1.3B. I am still working closely with the amazing team to design more features. Stay tunned!

<!-- <a href=""><button class="superbutton">NEXT PROJECT</button></a> -->