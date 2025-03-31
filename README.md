<h2>About This Page</h2>
<p>Hi, this is Aise Manuel. This reamde file provides a basic introduction to my static webpage created for a Web Technologies assignment where I provide and outline of my project.<br/><br/>
In this document, I include the rationale of the html structuring as well as the purpose for my css files. I also include the repository structure for asset management.</p>

<h2>Technologies Used</h2>
<ul>
    <li><strong>HTML</strong>: The backbone of the webpage, responsible for structuring the content.
        <ul>
            <li>Uses semantic elements (<code>&lt;header&gt;</code>, <code>&lt;section&gt;</code>, <code>&lt;footer&gt;</code>) to improve readability and SEO.</li>
            <li>Divides content into meaningful sections such as:
                <ul>
                    <li><strong>Header:</strong> Contains the title or introduction.</li>
                    <li><strong>Main Section:</strong> Includes the primary content, such as the about me section and a gallery of favorite gadgets.</li>
                    <li><strong>Footer:</strong> Provides social links or additional resources.</li>
                </ul>
            </li>
            <li>Uses <code>&lt;img&gt;</code> tags to display images, ensuring they are properly referenced from the <code>images/</code> folder which also include alt texts for accessibility.</li>
            <li>Includes navigation links using <code>&lt;a&gt;</code> tags to allow users to explore external profiles (e.g., LinkedIn, GitHub).</li>
        </ul>
    </li>
    <li><strong>CSS (Cascading Style Sheets)</strong>: Used to style the webpage and enhance its visual appeal.
        <ul>
            <li>Responsible for defining the font styles, colors, layouts, and responsiveness.</li>
            <li>Includes multiple CSS files for better maintainability:
                <ul>
                    <li><strong>style.css</strong>: The primary stylesheet responsible for overall layout, spacing, and typography.</li>
                    <li><strong>styleguide.css</strong>: Contains reusable design components, such as button styles, color themes, and typography guidelines.</li>
                    <li><strong>globals.css</strong>: Manages foundational styles, including margin resets, font normalization, and base design elements.</li>
                </ul>
            </li>
        </ul>
    </li>
<li><strong>GitHub Pages</strong>: A free hosting service that allows this static webpage to be deployed online.</li>
</ul>


<h2>Repository Structure</h2>
<pre>
aisemanuel
├── globals.css       
│── images/           
    ├── bose-700.jpg
    ├── ghibli-portrait.jpg
    ├── github.jpg
    ├── ipad-mini-6.jpg
    ├── keychron.jpg
    ├── linkedin.png
│── index.html        
├── style.css         
├── styleguide.css    
│── README.md        
</pre>

<h2>How to View the Page</h2>
<p>Once deployed, the page will be accessible at:</p>
<p><a href="https://aisemanuel.github.io/" target="_blank">https://aisemanuel.github.io/</a></p>
