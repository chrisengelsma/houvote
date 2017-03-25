# README

Houvote

Get info on elected and unelected government

## Structure

<pre>
governments
  slug
  name
  level {special,city,county,state,federal}
  geom

terms
  government_slug
  person_slug
  name            # e.g. chair 1, optional
  start_date
  end_date

people
  slug
  photo_url
  name
  born


elections
  government_slug
</pre>


## Layers of government

* Voting Precinct
  * DNC chair
  * GOP chair

* School District Board

* Community College Board

* TIRZ (U)

* City
  * Mayor
  * Controller
  * District Council Members
  * At-Large Council Members

* County
  * Judge
  * Commissioners
  * Clerk
  * County Attorney
  * District Attorney
  * District Clerk
  * Sheriff
  * Tax Assessor-Collector
  * Treasurer
  * Constables
  * County Civil Courts at Law 	  	
  * County Criminal Courts at Law 	  	
  * Court of Appeals - First 	  	
  * Court of Appeals - Fourteenth 	  	
  * District Civil Courts 	  	
  * District Criminal Courts 	  	
  * District Family Courts 	  	
  * District Juvenile Courts 	  	
  * Justice of the Peace Courts 	  	
  * Probate Courts

  * DNC Chair

* MUD / Water Improvement District

* Special Improvement District

* State
  * Governor
  * Lt. Governor
  * Attorney General
  * House Rep
  * Senate
  * Railroad Commission
  * State Board of Education

  * DNC Chair

* US House Rep

* US Senate

* Prez obv
