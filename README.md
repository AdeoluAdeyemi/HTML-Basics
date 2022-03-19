# HTML-Basics
<h1>Summary</h1>
        <p>I've come to discover that the best way to master any knowledge is through the owner's manual. Hence, I'm unlearning web design(HTML) from classroom and online lessons, and relearning using the creator's <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body#attr-onbeforeprint">manual</a>.</p>
        <p>I've discovered some amazing simple solutions that exist using markups and attributes that I ordinarily would have applied instead of multiline of Javascript scripts statements. e.g:</p>
        <ol>
            <li>
                <p>Refresh/Redirect a page using <br/> <br/>
                    <strong>
                        &lt;meta http-equiv="refresh" content="300" /&gt;
                    </strong> or <br/> <br/>
                    <strong>
                        &lt; http-equiv="refresh" content="300;url=https://www.google.com" /&gt;
                    </strong>   <br/> <br/> 
                </p>
                <code>
                
                    function autoRefreshPage()
                        {
                            window.location = window.location.href;
                        }

                    setInterval('autoRefreshPage()', 600000); 
                </code> 
            </li>
            <li>
                <p>Internet Connection Notification</p>
                <p>Imagine being able to notify user of internet disconneciton from you application GUI using only markup attributes? It\'s this simple.</p>
                <strong>
                    &lt;body onoffline="alert('Internet connection lost! Check your network!');" ononline="alert('You are back online!');"&gt;               
                </strong> 
            </li>
        </ol>