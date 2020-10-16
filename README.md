### abdulmukit98.github.io

	git config --global user.name "Your name"
	git config --global uuser.email "Your emaill"
	
	git clone https://github.com/abdulmukit98/abdulmukit98.github.io.git
	git status
	git add --all
	git commit -m "new commit"
	git push -u origin master

### pull

	pull overwrite local file and match to remote repo
	creat a file in remote repo
	pull it to local repo

	in abdulmukit98.github.io folder
	git pull https://github.com/abdulmukit98/abdulmukit98.github.io.git
	or sumply git pull

### force pull
	
	in abdulmukit98.github.io path
	git fetch --all
	git reset --hard origin/master

### syntax 

[lesson](https://www.youtube.com/watch?v=lusCM67ZvNM)<br>

    highlight.js
    <link rel="stylesheet"
      href="//cdn.jsdelivr.net/gh/highlightjs/cdn-release@10.2.1/build/styles/default.min.css">
    
    <script src="//cdn.jsdelivr.net/gh/highlightjs/cdn-release@10.2.1/build/highlight.min.js"></script>
    <script>hljs.initHighlightingOnLoad();</script>

### HTML Entity
<h3>
https://www.w3schools.com/html/html_entities.asp<br>
https://www.freeformatter.com/html-entities.html<br>
</h3>


### embeds
    need a parent element with embed-responsive
    used for iframe, embed, video and objcec element
    
    <div class="embed-responsive embed-responsive-16by9">
        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/pVfj6mxhdMw"></iframe>
    </div> 
### responsive image
    <img class="img-fluid" style="max-width: 100%; height: auto" src="image/after.png">

### tool
* imagecolorpicker

### HTML include
    
    create the template.html        //this can be both elaborate or minified
        <div>
            Template Nav
        </div>
    
    on the main file 
        * add jquery script from https://code.jquery.com/
    
        * add div where the template will place
            <div id="header">

            </div>
        
        * add custom script file to link div with template.html
                <script>
                    $(function () {
                        $('#header').load('template.html');
                    });
                </script>
        
        
        * remember that jquery script must be initialize before custom js-script
        * hash sign # to indicate id (#header)
            we place # before id only when we call them
                $('#header').load('...');
            
            when initialize # dont use
            <div id = "header">
            
            
        
[visualize](https://www.youtube.com/watch?v=m_RInqNGwmo)<br>
    
    NB Dropdown menu in included navbar need 2 refresh + double-click