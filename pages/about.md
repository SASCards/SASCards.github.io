---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://images.pexels.com/photos/8668775/pexels-photo-8668775.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" %} 

{% include feature/nav-menu.html sections="About SAS Cards; Buy, trade and contact" %}

## About SAS Cards

### 🎯 Objective of SAS Cards

This digital record has a primary objective and a secondary objective that is a by-product of the original:

- The **primary objective** is  to help me manage my growing collection of business cards. It is very frustrating to find a card, have the card sound vaguely familiar, and have to check card by card to see if it is a duplicate. My collection method is simple: two cards are different if there is even **the slightest difference in printing** on them. For example, two business cards from a well-known restaurant chain, which at first glance look the same, are different to me because the address line on the back of the cards is different. This makes checking if the cards I add to my collection are duplicates an increasingly arduous task. With this digital register, I can check that in less than 5 seconds.

- The **secondary objective** is that you, the visitor of this website, can **see my collection** and **access my metadata**. Images are stored outside GiHub using Google Drive. If links are broken (i.e. images are not loading) let me know by e-mail, please!

### 📜 Nomenclature of card identifiers

SAS Cards have an identifier that follows this structure:

`sas[pack]_[xxx]`

- The first part is **always** the string `sas`.

- The second part, `[pack]`, represents the **number of the album** in which the card is physically stored. For example, the card `sas1_[xxx]` is stored in album 1. I use [these albums from Amazon](https://www.amazon.com/Business-Card-Storage-480-Cards/dp/B01HZO7ZOW/) for my collection (this is not advertising, it's just that they are good value for money).

- The third part, `[xxx]`, is a three-digit number that represents the **position of the card in the album**. For example, the card `sas1_001` is the first card of album 1. The albums I currently use have a capacity of 480 cards, so three digits are enough for this part of the identifier.

Sometimes the cards are **too large for the album**. In these cases, the second part of the identifier is not the album number, it is `XL`. For example, the card `sasXL_003` is the third large card of my collection. You can use the string `sasXL_` to [search for the large cards in my collection](https://sascards.github.io/browse.html#sasXL_).

## Buy, trade and contact

I am open to buy, sell or exchange business cards. If you have any interest in this, you can contact me at:

`sergioaliaseg[at]gmail[dot]com`

The e-mail is written that way to avoid spam bots. Replace `[at]` with "@" and `[dot]` with "."