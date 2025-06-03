<h1><a href="https://ai.mrsuhu.org">AI MR SUHU</a> - Open Source Generalist AI Agent</h1>

<p>(link : <a href="https://ai.mrsuhu.org">ai.mrsuhu.org</a> )</p>

<p>AI MR SUHU is a fully open source AI assistant that helps you accomplish real-world tasks with ease. Through natural conversation, AI MR SUHU becomes your digital companion for research, data analysis, and everyday challenges&mdash;combining powerful capabilities with an intuitive interface that understands what you need and delivers results.</p>

<p>AI MR SUHU&#39;s powerful toolkit includes seamless browser automation to navigate the web and extract data, file management for document creation and editing, web crawling and extended search capabilities, command-line execution for system tasks, website deployment, and integration with various APIs and services. These capabilities work together harmoniously, allowing AI MR SUHU to solve your complex problems and automate workflows through simple conversations!</p>

<h3>Backend API</h3>

<p>Python/FastAPI service that handles REST endpoints, thread management, and LLM integration with Anthropic, and others via LiteLLM.</p>

<h3>Frontend</h3>

<p>Next.js/React application providing a responsive UI with chat interface, dashboard, etc.</p>

<h3>Agent Docker</h3>

<p>Isolated execution environment for every agent - with browser automation, code interpreter, file system access, tool integration, and security features.</p>

<h3>Supabase Database</h3>

<p>Handles data persistence with authentication, user management, conversation history, file storage, agent state, analytics, and real-time subscriptions.</p>

<h2>Use Cases</h2>

<ol>
	<li>
	<p><strong>Competitor Analysis</strong> (Watch) - <em>&quot;Analyze the market for my next company in the healthcare industry, located in the UK. Give me the major players, their market size, strengths, and weaknesses, and add their website URLs. Once done, generate a PDF report.&quot;</em></p>
	</li>
	<li>
	<p><strong>VC List</strong> (Watch) - <em>&quot;Give me the list of the most important VC Funds in the United States based on Assets Under Management. Give me website URLs, and if possible an email to reach them out.&quot;</em></p>
	</li>
	<li>
	<p><strong>Looking for Candidates</strong> (Watch) - <em>&quot;Go on LinkedIn, and find me 10 profiles available - they are not working right now - for a junior software engineer position, who are located in Munich, Germany. They should have at least one bachelor&#39;s degree in Computer Science or anything related to it, and 1-year of experience in any field/role.&quot;</em></p>
	</li>
	<li>
	<p><strong>Planning Company Trip</strong> (Watch) - <em>&quot;Generate me a route plan for my company. We should go to California. We&#39;ll be in 8 people. Compose the trip from the departure (Paris, France) to the activities we can do considering that the trip will be 7 days long - departure on the 21st of Apr 2025. Check the weather forecast and temperature for the upcoming days, and based on that, you can plan our activities (outdoor vs indoor).&quot;</em></p>
	</li>
	<li>
	<p><strong>Working on Excel</strong> (Watch) - <em>&quot;My company asked me to set up an Excel spreadsheet with all the information about Italian lottery games (Lotto, 10eLotto, and Million Day). Based on that, generate and send me a spreadsheet with all the basic information (public ones).&quot;</em></p>
	</li>
	<li>
	<p><strong>Automate Event Speaker Prospecting</strong> (Watch) - <em>&quot;Find 20 AI ethics speakers from Europe who&#39;ve spoken at conferences in the past year. Scrapes conference sites, cross-references LinkedIn and YouTube, and outputs contact info + talk summaries.&quot;</em></p>
	</li>
	<li>
	<p><strong>Summarize and Cross-Reference Scientific Papers</strong> (Watch) - <em>&quot;Research and compare scientific papers talking about Alcohol effects on our bodies during the last 5 years. Generate a report about the most important scientific papers talking about the topic I wrote before.&quot;</em></p>
	</li>
	<li>
	<p><strong>Research + First Contact Draft</strong> (Watch) - <em>&quot;Research my potential customers (B2B) on LinkedIn. They should be in the clean tech industry. Find their websites and their email addresses. After that, based on the company profile, generate a personalized first contact email where I present my company which is offering consulting services to cleantech companies to maximize their profits and reduce their costs.&quot;</em></p>
	</li>
	<li>
	<p><strong>SEO Analysis</strong> (Watch) - <em>&quot;Based on my website AI MR SUHU.so, generate an SEO report analysis, find top-ranking pages by keyword clusters, and identify topics I&#39;m missing.&quot;</em></p>
	</li>
	<li>
	<p><strong>Generate a Personal Trip</strong> (Watch) - <em>&quot;Generate a personal trip to London, with departure from Bangkok on the 1st of May. The trip will last 10 days. Find an accommodation in the center of London, with a rating on Google reviews of at least 4.5. Find me interesting outdoor activities to do during the journey. Generate a detailed itinerary plan.&quot;</em></p>
	</li>
	<li>
	<p><strong>Recently Funded Startups</strong> (Watch) - <em>&quot;Go on Crunchbase, Dealroom, and TechCrunch, filter by Series A funding rounds in the SaaS Finance Space, and build a report with company data, founders, and contact info for outbound sales.&quot;</em></p>
	</li>
	<li>
	<p><strong>Scrape Forum Discussions</strong> (Watch) - <em>&quot;I need to find the best beauty centers in Rome, but I want to find them by using open forums that speak about this topic. Go on Google, and scrape the forums by looking for beauty center discussions located in Rome. Then generate a list of 5 beauty centers with the best comments about them.&quot;</em></p>
	</li>
</ol>

<h2>Self-Hosting</h2>

<p>AI MR SUHU can be self-hosted on your own infrastructure using our setup wizard. For a comprehensive guide to self-hosting AI MR SUHU, please refer to our Self-Hosting Guide.</p>

<p>The setup process includes:</p>

<ul>
	<li>Setting up a Supabase project for database and authentication</li>
	<li>Configuring Redis for caching and session management</li>
	<li>Setting up Daytona for secure agent execution</li>
	<li>Integrating with LLM providers (Anthropic, OpenAI, Groq, etc.)</li>
	<li>Configuring web search and scraping capabilities</li>
</ul>

<h3>Quick Start</h3>

<ol>
	<li><strong>Clone the repository</strong>:</li>
</ol>

<pre>
git clone https://github.com/kortix-ai/AI MR SUHU.git
cd AI MR SUHU</pre>

<ol>
	<li><strong>Run the setup wizard</strong>:</li>
</ol>

<pre>
python setup.py</pre>

<ol>
	<li><strong>Start or stop the containers</strong>:</li>
</ol>

<pre>
python start.py</pre>

<h3>Manual Setup</h3>

<p>See the Self-Hosting Guide for detailed manual setup instructions.</p>

<p>The wizard will guide you through all necessary steps to get your AI MR SUHU instance up and running. For detailed instructions, troubleshooting tips, and advanced configuration options, see the Self-Hosting Guide.</p>

<h2>Contributing</h2>

<p>We welcome contributions from the community! Please see our Contributing Guide for more details.</p>

<h2>Acknowledgements</h2>

<h3>Main Contributors</h3>

<ul>
	<li>Adam Cohen Hillel</li>
	<li>Dat-lequoc</li>
	<li>Marko Kraemer</li>
</ul>

<h3>Technologies</h3>

<ul>
	<li>Daytona - Secure agent execution environment</li>
	<li>Supabase - Database and authentication</li>
	<li>Playwright - Browser automation</li>
	<li>OpenAI - LLM provider</li>
	<li>Anthropic - LLM provider</li>
	<li>Tavily - Search capabilities</li>
	<li>Firecrawl - Web scraping capabilities</li>
	<li>RapidAPI - API services</li>
</ul>

<h2>License</h2>

<p>Kortix AI MR SUHU is licensed under the Apache License, Version 2.0. See LICENSE for the full license text.</p>
