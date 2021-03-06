# HTML-Basics
<h1>Summary</h1>
<p>Mastery of any knowledge requires a careful examination of the owner's manual. </p> 
<p>I've taken a bold step to unlearn Web Design(HTML) based on my classroom and online lessons, and relearn using the creator's <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body#attr-onbeforeprint">manual</a>. </p>
<p>Within the first 1 hour of my careful review, I discovered amazing simple solutions that exist using markups and attributes that I ordinarily would have applied instead of multiline of Javascript scripts statements.</p>
<p>For instance:</p>
 <ol>
    <li>
        <p>Refresh/Redirect a page using <br/> <br/>
            <strong>
                &lt;meta http-equiv="refresh" content="300" /&gt;
            </strong> or <br/> <br/>
            <strong>
                &lt;meta http-equiv="refresh" content="300;url=https://www.google.com" /&gt;
            </strong> 
        </p>
        <p>       
            Instead of a Javascript function <br/>         
            <code>
                function autoRefreshPage()
                    {
                        window.location = window.location.href;
                    }
                setInterval('autoRefreshPage()', 600000); 
            </code> 
        </p>
    </li>
    <li>
        <p>Internet Connection Notification</p>
        <p>Imagine being able to notify a user of internet disconneciton from within your application using only markup attributes? It's this simple.</p>
        <strong>
            &lt;body onoffline="alert('Internet connection lost! Check your network!');" ononline="alert('You are back online!');"&gt;               
        </strong> 
    </li>
</ol>