




<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">
  </head>
  <body>
</a>Visualizing Data</h1>
<h2><a id="user-content-preview" class="anchor" aria-hidden="true" href="#preview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Preview</h2>
<p>In the final assignment are presented visualized data, taken from NESARC codebook, in order to examine the correlation between cannabis use and mental disorders such as major depression and general anxiety diagnosed in the last 12 months in a sample of  9535 U.S. young adults, aged from 18 to 30 years old. I used Spyder IDE to create both univariate and bivariate bar charts for the selected variables. More specifically, with variable ‘AGE’ between 18 and 30, I built unvariate graphs for categorical variables <strong>‘S3BQ1A5’</strong> which represents cannabis use, <strong>‘S3BD5Q2E’</strong>  which is frequency of this use, <strong>‘MAJORDEP12’</strong> that stands for major depression diagnosis in the last 12 months and <strong>‘GENAXDX12’</strong> that indicates general anxiety diagnosis in the same period. In addition, you will find another univariate graph for the quantitative variable  <strong>‘NUMJOPMOTH_EST’</strong>, which I created in my previous assignment by multiplying frequency of cannabis use and average quantity of joints smoked, in order to estimate the total number of joints smoked per month by the individuals. As far as the bivariate graphs are concerned, I chose to examine visualized the association between cannabis use (C-&gt;C) and both mentioned disorders and additionally the relationship between frequency (C-&gt;C) and quantity (Q-&gt;C) of this use with both depression and anxiety. Thus, bar charts were created combining variables  <strong>‘S3BQ1A5’</strong> (cannabis use), ‘S3BD5Q2E’ (frequency of use) and <strong>‘NUMJOPMOTH_EST’</strong> (quantity of joints) with variables <strong>‘MAJORDEP12’</strong> (major depression) and  <strong>‘GENAXDX12’</strong> (general anxiety). Concluding, for the quantitative variable both center and spread were measured and describe function was used in order to examine useful information, about the selected categorical variables.</p>
<h2><a id="user-content-output" class="anchor" aria-hidden="true" href="#output"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Output</h2>
<h3><a id="user-content-univariate-graphs" class="anchor" aria-hidden="true" href="#univariate-graphs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Univariate graphs:</h3>
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out1.png"><img src="https://github.com/Gkontopodis/Data-Management-Visualization/raw/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out1.png" alt="out1" style="max-width:100%;"></a></p>
<p>A random sample of 9535 U.S. young adults, aged 18-30, were asked, as a part of NESARC survey, the following question: “Have you ever used cannabis?” A percentage of 25.29% (or 7042 individuals) answered “Yes”, whereas 73.85% (or about 2500 individuals) answered “No” which was the most frequent answer. Also a significantly small percentage of 0.84%, fell into category 9 (“Unknown“) which is our missing data.</p>
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out2.png"><img src="https://github.com/Gkontopodis/Data-Management-Visualization/raw/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out2.png" alt="out2" style="max-width:100%;"></a></p>
<p>To the question of “How often did you use cannabis when using the most?”, the top answer was “Every day”, since 534 individuals fell into this category, followed by “Once a year” category with approximately 400 individuals. Less than 100 people chose “7-11 times per year” category, which was the least frequent answer.</p>
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out3.png"><img src="https://github.com/Gkontopodis/Data-Management-Visualization/raw/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out3.png" alt="out3" style="max-width:100%;"></a></p>
<p>Of the total number of participants (18-30) who answered “Yes” to the question of cannabis use, only those who were smoking marijuana in last 12 months and prior were taken into consideration for the next two questions.</p>
<p>To the question of “Have you been diagnosed with non-hierarchical major depression in the last 12 months?”, about 660 participants or 79.04% answered “No” which was the most frequent answer, whereas 175 or 20.95% fell into “Yes”.</p>
<p>For the question, ”Have you been diagnosed with non-hierarchical generalized anxiety in the last 12 months?”, 802 individuals or 96.04% answered “No“ that was our top answer, while only 33 or 3.95% chose “Yes“.</p>
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out4.png"><img src="https://github.com/Gkontopodis/Data-Management-Visualization/raw/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out4.png" alt="out4" style="max-width:100%;"></a></p>
<p>For the estimated number of joints smoked per month by cannabis users, ages 18-30, it noticeable from the graph that there was a skewed-right distribution. The spread or the standard deviation of the variable is extremely large which indicates a large variety of answers among the participants. The three main numerical measures of the center of the distribution are the mode, the median, and the mean. Here we can see that mode is equal to 0.1 and it was the most common occurring value in the distribution, which means that most of participants smoked less than 1 joint per month. The mean is equal to 70.1 which indicates that cannabis users smoked about 70 joints per month on average and the median or the middle value is 6.</p>
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out5.png"><img src="https://github.com/Gkontopodis/Data-Management-Visualization/raw/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out5.png" alt="out5" style="max-width:100%;"></a></p>
<p>Estimated number of joints smoked per month binned to groups as illustrated above. Another way of visualizing the distribution of variable <strong>‘NUMJOPMOTH_EST’</strong>. We can see that most individuals, about 990, smoked less than one joint per month and the shape of the distribution is right-skewed.</p>
<h3><a id="user-content-bivariate-graphs" class="anchor" aria-hidden="true" href="#bivariate-graphs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Bivariate graphs:</h3>
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out6.png"><img src="https://github.com/Gkontopodis/Data-Management-Visualization/raw/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out6.png" alt="out6" style="max-width:100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out7.png"><img src="https://github.com/Gkontopodis/Data-Management-Visualization/raw/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out7.png" alt="out7" style="max-width:100%;"></a></p>
<p>In the bar charts above we can see the relationship between quantity of joints smoked per month by cannabis user, aged 18 to 30 years old, and both major depression (first) and general anxiety (second) diagnoses in the last 12 months (Q-&gt;C). The explanatory variable is quantity of joints (quantitative), while the response variables are depression and anxiety diagnoses (categorical). There is a slightly increasing trend in the first graph, but not in the second.</p>
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out10.png"><img src="https://github.com/Gkontopodis/Data-Management-Visualization/raw/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out10.png" alt="out10" style="max-width:100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out11.png"><img src="https://github.com/Gkontopodis/Data-Management-Visualization/raw/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out11.png" alt="out11" style="max-width:100%;"></a></p>
<p>In the graphs presented above we can see the correlation between frequency of cannabis use and both major depression and general anxiety (C-&gt;C). The explanatory variable is frequency of cannabis use (categorical), while the response variables are depression and anxiety diagnoses (categorical). Again, for the first graph we have a right-skewed distribution, which indicates that the more an individual smoked cannabis, the better were the chances to get diagnosed with depression. However, we cannot support the same as far as anxiety is concerned, which appears to have a more raffle and abnormal distribution.</p>
<p><a target="_blank" rel="noopener noreferrer" href="https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out8.png"><img src="https://github.com/Gkontopodis/Data-Management-Visualization/raw/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out8.png" alt="out8" style="max-width:100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out9.png"><img src="https://github.com/Gkontopodis/Data-Management-Visualization/raw/master/Assignment%20Week%204/Graphs%20-%20Screenshots/out9.png" alt="out9" style="max-width:100%;"></a></p>
<p>The graphs presented above illustrate the association between cannabis use and both major depression and general anxiety diagnoses in young adults, aged from 18 to 30 years old, in the last 12 months (C-&gt;C). The explanatory variable is cannabis use (categorical) and the response variables are depression and anxiety diagnoses (categorical).</p>
<h2><a id="user-content-summary" class="anchor" aria-hidden="true" href="#summary"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Summary</h2>
<p>To sum up, looking through the the last graphs, it can be noticed that there are some slight differences between the percentages of cannabis users compared to non-users. Major depression cases in cannabis users young adults (20.95%) seem to be slightly more than double compared to those of non-users (8.42%).In addition, general anxiety diagnoses in cannabis users (3.95%) appear to be also marginally more than double in comparison to the non-users (1.63%). It could be supported that there is a relative association between cannabis and such mental disorders, thus cannabis use increases the likelihood of meeting criteria for depression or general anxiety in the future. However, the sample is extremely small and it is unclear how representative it is, making the findings less reliable, since a large amount of error may be involved.</p>
</article>
  </div>

    
  </div>

  </div>

        
<div class="footer container-xl width-full p-responsive" role="contentinfo">
    <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between flex-sm-items-center pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
      <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mr-lg-4" href="https://github.com">
        <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>
      <ul class="list-style-none d-flex flex-wrap col-12 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0">&copy; 2020 GitHub, Inc.</li>
          <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
          <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
            <li class="js-cookie-consent-preferences-link-container mr-3 mr-lg-0" hidden="hidden">
  <button data-ga-click="Footer, go to cookie preferences, text:cookie preferences" class="btn-link js-cookie-consent-preferences-link" type="button">Cookie Preferences</button>
</li>
          <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
          <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to help, text:help" href="https://docs.github.com">Help</a></li>
          <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://docs.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://services.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
          <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
          <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>
      </ul>
    </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v-2.5z"></path></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path></svg>
    </button>
    You can’t perform that action at this time.
  </div>


  <div class="js-stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v-2.5z"></path></svg>
    <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

 

  </body>
</html>

