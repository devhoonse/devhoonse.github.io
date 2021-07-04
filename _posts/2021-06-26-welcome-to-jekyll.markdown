---
layout: post
title:  "이곳은 DevHoonse 의 블로그입니다."
date:   2021-06-26 23:02:25 +0900
categories: devhoonse hello
---
안녕하세요, 이곳은 `DevHoonse` 의 블로그입니다.

잊어선 안될 것들을 남길 `비망록` 혹은 `노트` 그 중간 어디쯤으로 사용되는 공간입니다.


{% highlight javascript %}
const DevHoonse = (function() {
    const _SKILLS = ['Javascript', 'PYTHON', 'Django', 'Flask'];
    const _PORTFOLIOS = [];
    return {
        getSkills: function() {
            return this._SKILLS;
        },

        addSkill: function(skill) {
            this._SKILLS.push(skill);
        },

        getPortfolios: function() {
            return this._PORTFOLIOS;
        },

        addPortfolio: function(work) {
            this._PORTFOLIOS.push(work);
        },
    }
})();
// it is me
{% endhighlight %}

테마로 사용된 `jekyll-plainwhite` 에 대해 궁금하시면? [여기로~][jekyll-plainwhite]

[jekyll-plainwhite]: https://github.com/samarsault/plainwhite-jekyll
