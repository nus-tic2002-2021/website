<div id="title">

## Project → mid-v1.2 [week 8]
</div>
<div id="body">

<tip-box>

Overview: <include src="project-deliverables.md#mid-v12-overview" inline />
</tip-box>

<div id="product">

**<big>Project Management:</big>**

* Complete the repo set up
  * Fix any errors in org/repo set up %%&nbsp;(e.g. wrong repo name)%%.
  * Set up [auto-publishing of docs](https://nus-cs2103-ay1718s2.github.io/addressbook-level4/UsingTravis.html#enabling-auto-publishing-of-documentation) if you haven't done so already

* Adjust project rigor to suit your team's pace

  * Automated tests have benefits, but they can be a pain to write/maintain; GUI tests are especially hard to maintain because their behavior can sometimes depend on things such as the OS, resolution etc.
  
    It is OK to get rid of some of the troublesome tests and rely more on manual testing instead. The less automated test coverage you have, the higher the risk of regressions; but it may be an acceptable trade-off under the circumstances if tests are slowing you down too much. There is no direct penalty for removing GUI tests.
  
    Also note <trigger trigger="click" for="modal:v12-testingExpectations">our expectation on test code</trigger>. 
    
  * You can also reduce the rigor of checkstyle checks to expedite PR processing.
  * Another thing you can do is to switch to a simpler workflow if the forking workflow is slowing you down. 

<modal title="Admin {{ icon_embedding }} Project Asessement → Expectation on testing" id="modal:v12-testingExpectations">
  <include src="project-testing.md#expectations"/>
</modal>

* **Start proper milestone management**

  * :exclamation: Starting from the upcoming milestone, ==there are additional requirements to follow== regarding how you **use GitHub to manage your milestones**, as described in <trigger trigger="click" for="modal:v12-projectTracking">[Admin {{ icon_embedding }} Appendix E: GitHub: Project Schedule Tracking]</trigger>.

* As before, you are _recommended_ (but not required) to **follow the forking workflow** when evolving the product.

<modal large title="Admin {{ icon_embedding }} Appendix E: Github: Project Schedule Tracking" id="modal:v12-projectTracking">
  <include src="appendixE-gitHub.md#project-schedule-tracking"/>
</modal>

**<big>Product:</big>**

* **From v1.2 onwards each member is expected to contribute <tooltip content="the amount of code does not matter; even small contributions are acceptable">some</tooltip> code to each <tooltip content="v1.3, v1.4"> milestone</tooltip>, preferably each week; only merged code is considered as contributions** %%<popover content="The ability to deliver code incrementally is an important LO of this module because incremental delivery improves the _visibility_ of your work.">(Reason)</popover>%%. <br>
 If an enhancement is too big to complete in one milestone, try to deliver it in smaller incremental steps e.g. deliver a basic version of the enhancement first. 


</div>

</div>