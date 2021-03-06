---
layout: page
title: "API Release Kit"
---
  
<table style="width: 100%;" border="0" cellpadding="2" cellspacing="2">
<ul>
    <tr>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#homepage">Homepage</a></li></td>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#documentation">Documentation</a></li></td>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#code-samples">Code Samples</a></li></td>
    </tr>
    <tr>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#interactive-sample">Interactive Samples</a></li></td>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#sdks">SDKs</a></li></td>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#api-key-management">API Key Management</a></li></td>
    </tr>
    <tr>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#issue-tracker">Issue Tracker</a></li></td>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#contact-info">Contact Info</a></li></td>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#api-roadmap">API Roadmap</a></li></td>
    </tr>
    <tr>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#changelog">Changelog</a></li></td>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#faq">FAQ</a></li></td>
        <td style="text-align: left; width: 33%;"><li><a href="https://pages.18f.gov/API-All-the-X/pages/api_release_kit#widgets">Widgets</a></li></td>
    </tr>
    </ul>
</table>


## Homepage  
Each of your public APIs needs a page to serve as a hub to provide access to all information and tools associated with it. By using the page’s sidebar, footer, and sub pages, you can directly include or link to each of the following components that exist for the API. This allows for ready discovery of anything a potential developer may need, minimizing the effort that is asked of them and maximizing the adoption. This API homepage should be a webpage, not a downloadable Word or PDF file, in order to provide ease of use as well as a further degree of permanence.  
Your team should decide which of the following elements to include with your API, recognizing that ensuring a well-rounded and fully functional developer experience is the best recipe for your API’s success. The below list represents elements you should assemble with each API. Examples and suggested tools are included and can be readily copied and improved upon between agencies.

## Documentation  
API documentation should include all instructions and details necessary or useful for visiting developers who wish to use the API. Common elements include:
* Description of functionality and available information 
* Protocol and format 
* List of end points 
* Example API calls 
* Error response codes 
* Other remaining items from this list 
This information is often listed in the body of the API homepage and should be generated by the API's technical producer or by any tools that have been used to generate the API itself. The API's technical producer should produce the documentation, but by reviewing the documentation of other .gov APIs, you can decide what material is most important for you to also include.

## Code Samples  
By including sample code snippets that consume the API in the API’s documentation, you provide easy-to-understand case studies for developers to clone, modify, and learn from. Where possible, provide working samples in popular programming languages, such as Javascript, PHP, Ruby, or Python.

### Potential Tools  
* Embedded [GtHub gist](https://gist.github.com/)
* '<code>' html tags

### .Gov Examples
* [Department of Labor](http://developer.dol.gov/)
* [Federal Register](https://www.federalregister.gov/blog/learn/developers)
* [National Renewable Energy Laboratory](http://developer.nrel.gov/doc/api/georeserv/app/sam/pvwatts#demo-application)
* [National Weather Service](http://graphical.weather.gov/xml/mdl/XML/Design/WFS_example.php)
* [EnergyStar.gov](https://data.energystar.gov/developers/docs/energy-star-certified-clothes-washers)
* [HealthIndicators.gov](http://healthindicators.gov/Developers/Examples)

## Interactive Sample
In addition to static code examples, you can also provide interactive tools that allow developers to modify the examples and see the change in results. This simple addition supports a quick path towards understanding how the API functions.

### Potential Tools 
* [Swagger](http://swagger.wordnik.com/)
* [I/O Docs](https://github.com/mashery/iodocs)

### .Gov Examples  
* [Consumer Financial Protection Bureau](cfpb.github.io/api/hmda/console/)
* [EnergyStar.gov](https://data.energystar.gov/developers/docs/energy-star-certified-clothes-washers)
* [Federal Register](https://www.federalregister.gov/blog/learn/developers)
* [Food and Drug Administration](https://open.fda.gov/drug/event/)
* [GSA - Discovery](https://discovery.gsa.gov/docs/)
* [GSA - System for Award Management](http://gsa.github.io/sam_api/sam/console/)
* [National Renewable Energy Laboratory](http://developer.nrel.gov/docs/transportation/transportation-incentives-laws-v1/)
* [Regulations.gov](http://regulationsgov.github.io/developers/console/)


## SDKs 
Software Development Kits (SDKs) are small software libraries that make it easy to employ the associated API with a specific programming language, such as PHP or Ruby. Because many developers have a programming language of choice, you can ensure faster adoption by more developers by offering these in many popular languages. SDKs are often hosted as projects in your agency’s GitHub account, but should also be linked from the API’s homepage.  

### .Gov Examples  
* [Department of Labor](http://developer.dol.gov/)
* [Environmental Protection Agency](http://www.epa.gov/developer/sdk_sample.html)

## API Key Management  
If developers are required to request an API key, the entire experience should be self-service and allow the developer to move forward once the key has been issued. When an agency is publishing multiple APIs that use keys, a developer should be able to use the same key for each API instead of needing to register and keep track of individual ones.

### Potential Tools 
* [API.Data.gov](http://api.data.gov/)

### .Gov Examples  
* [Department of Labor](https://devtools.dol.gov/developer)
* [Census Bureau](http://www.census.gov/developers/)
* [National Climate Data Center](http://www.ncdc.noaa.gov/cdo-web/token)
* [National Renewable Energy Laboratory](http://developer.nrel.gov/signup)
* [Federal Motor Carrier Safety Administration](https://mobile.fmcsa.dot.gov/developer/home.page)
* [EnergyStar.gov](https://data.energystar.gov/developers/docs/energy-star-certified-clothes-washers)

## Issue Tracker  
Developers need a clear and transparent means of reporting bugs or other issues that affect the API, and the API producer needs a functional means of managing these items. By doing this, the agency ensures the best customer service and incentivizes API adoption. Issue trackers can be stood up for each API individually, though it is more common to maintain one aggregate tracker to be made available at the developer hub level.
Free and open-source tools exist for this function, but possibly the quickest and easiest means is to create a stand-alone repository for the API in the agency’s GitHub account and employ the Issue Tracker functionality to receive and process developer feedback. In addition to being free, scalable, and requiring no infrastructure, this choice also has the added benefit of existing within the GitHub ecosystem, which is the norm within the developer community. This option also allows agency staff or other developers to subscribe to updates and receive alerts.

### Potential Tools 
* [GitHub Issue Tracker](http://apievangelist.com/2012/09/23/api-issue-management-with-github/)

### .Gov Examples  
* [Department of Labor](https://github.com/USDepartmentofLabor/DOLAPI/issues)

## Contact Info 
Developers need to have the ability to contact agency staff directly, so it's important to offer contact information for an API point of contact. This is often done in agencies by creating an email account at developer@agency.gov and forwarding it to one or several staff who work to field the incoming messages. This would allow the same contact information to be published at the developer hub instead of requiring a unique point of contact to be listed for each API.

### .Gov Examples  
* [Department of Labor](http://developer.dol.gov/contactfollow-us)
* [Department of Energy](http://energy.gov/developer-resources)
* [National Broadband Map](http://broadbandmap.gov/developer)
* [National Renewable Energy Laboratory](http://developer.nrel.gov/community)
* [U.S. Courts—PACER](http://www.pacer.gov/cmecf/developer/)

## API Roadmap
Any API will be more successful the more that its producers communicate with potential developers and inform them of the near- and long-term plans for the service. One easy means of doing this is to articulate these plans via milestones. This can be done in many ways, but one convenient and productive method is to employ the milestones functionality of GitHub in the same fashion as with Issue Tracking (it is actually integrated within the Issues section of any repository, alongside the issue tracker, but can be used in parallel). This allows agency staff or other developers to subscribe to updates and receive alerts.

### Potential Tools 
* [GitHub Milestones](http://apievangelist.com/2012/11/12/communicate-your-api-roadmap-with-github)

### .Gov Examples
* [Environmental Protection Agency](http://www.epa.gov/developer/ef_api.html#future)

## Changelog  
Over time, your API design may change and the documentation updated. Providing a changelog allows your developers to see at a glance what has changed and to better understand what impact the changes may have on their use of your API. This can be done through API version control, with each update receiving a version number and including a bulleted list of changes. It's also helpful to provide clear track changes to the API documentation, a task that is automatically integrated into any documentation you publish through GitHub. By posting the full text in GitHub, all future edits will clearly reflect changes so your developers can see at a glance what they need to know.

### Potential Tools 
* [GitHub](http://apievangelist.com/2012/10/24/version-control-your-api-documentation-with-github/)

### .Gov Examples  
* [National Weather Service](http://graphical.weather.gov/xml/#xml_changes)
* [Commerce—Automated Export System](http://www.aesdirect.gov/support/weblink_api_updates.html)
* [HealthIndicators.gov](http://healthindicators.gov/Developers/ReleaseNotes)

## FAQ  
Any common developer questions may reflect confusion held by other potential users. Maintaining a short list of frequently asked questions and answers provides a simple utility today as well as a good catch-all for future disclaimers and loose information that may come to mind in the future.

### .Gov Examples  
* [Department of Labor](http://developer.dol.gov/frequently-asked-questions)
* [National Institute on Drug Abuse](http://www.drugabuse.gov/developers/nmassist/faq)
* [National Weather Service](http://graphical.weather.gov/xml/)

## Widgets  
A particularly advanced way to drive adoption of your API is to also offer embeddable widgets that consume the API for use by developers and non-experts alike. Many sources of data are clear candidates for widgets that offer the most recent or popular items from the material. APIs allow advanced integration of this data, but by offering simple widgets that non-experts can use for common implementations, the faster, easier turnaround for third-parties will drive interest and adoption at all levels.

### .Gov Examples
* [Federal Communications Commission](http://my.fcc.gov/dashboard)
* [AIDSinfo](http://aidsinfo.nih.gov/widgets)

