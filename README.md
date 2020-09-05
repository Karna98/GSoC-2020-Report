<h1 align="center"> Google Summer of Code 2020 </h1>
<p align="center"><i>with</i> </p>
<h2 align="center"><a href="https://summerofcode.withgoogle.com/organizations/5003360748437504/">Cuneiform Digital Library Initiative (CDLI)</a></h2>

![GSoC with CDLI](assets/banner.png)

<h2 align="center"><i>Project Report on "<a href="https://summerofcode.withgoogle.com/projects/#4558611868549120">Improving CDLI Framework</a>" </i> </h2>

## About the project

The main aim of this project was to improve the CDLI framework.

The project focuses on: 
1. Building an authentication and authorization system for the framework.
2. Integrating Elastic Search for Simple Search.
3. Optimizing queries for Advance Search.
4. Preparing search results (Expanded and Compact format) with data pre-processing.

### Links

- [Proposal](https://github.com/cdli-gh/Framework/blob/master/Proposal/2020/Improving_CDLI_Framework.pdf)
- [Weekly Blogs](https://cdli-gh.github.io/blog/gsoc20/search/index)

## Team

- Vedant S. Wakalkar - Mentee
- Émilie Pagé-Perron - Mentor

## Technologies

- CakePHP 3
- Elastic Search
- Docker
- Javascript
- HTML


## Objectives Accomplished

1. Extend authorization/authentication system    
   - ByPassing 2FA ​(TwoFactorAuthentication)

      <table>
         <tr>
            <td>
               Login
            </td>
            <td>
               Register
            </td>
         </tr>
         <tr>
            <td>
               <center><img src="assets/demo/gifs/Bypassing_2FA_Login.gif" width="400" height="225"></center>
            </td>
            <td>
               <center><img src="assets/demo/gifs/Bypassing_2FA_Register.gif" width="400" height="225"></center>
            </td>
         </tr>
      </table>

   - Setting up Role based Access System.
   - Strong Password checker.
   - Implement Password Retrieval.
   - Fix ‘/logout’
      
      <center><img src="assets/demo/gifs/Logout.gif" width="800" height="450"></center>

   - Making Account Inactive (After inactivity period more than 6 months).
2. Simple Search

   <center><img src="assets/demo/gifs/Simple_Search.gif" width="800" height="450"></center>

3. Advanced Search
   
   <center><img src="assets/demo/gifs/Advanced_Search.gif" width="800" height="450"></center>

4. Search funtionality 
   - Search Settings
      
      <center><img src="assets/demo/gifs/Search_Settings.gif" width="800" height="450"><center>

   - Filters

      <center><img src="assets/demo/gifs/Filters.gif" width="800" height="450"><center>

   - Expanded and Compact View

      <center><img src="assets/demo/gifs/Expanded_and_Compact_view.gif" width="800" height="450"><center>

4. RocketChat Integration

## Contributions

* [Merge Requests](https://gitlab.com/cdli/framework/-/merge_requests?scope=all&utf8=%E2%9C%93&state=merged&author_username=Karna98)

* [Issues Created](https://gitlab.com/cdli/framework/-/issues?scope=all&utf8=%E2%9C%93&state=opened&author_username=Karna98)

## To Do (Post GSoC)

* Upgrade Simple Search: Add filter Supports.
* Documentation (Modules which are yet to be documented).

## Acknowledgement

* I would like to thank my mentor [Émilie Pagé-Perron](mailto:epp@ucla.edu) for helping and guiding me and also other mentees for collaboration throughout the GSoC journey!

* I am thankful to Google Summer Of Code for providing me an opportunity to work with CDLI.


## Demo Video 

Will be updated Soon.
