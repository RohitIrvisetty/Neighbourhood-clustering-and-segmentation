# Neighbourhood-clustering-and-segmentation

1)Following data sources will be needed to extract/generate the required information:, https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

2)centers of candidate areas will be generated algorithmically and approximate addresses of centers of those areas will be obtained using Geocoder

3)number of restaurants and their type and location in every neighborhood will be obtained using Foursquare API

4)coordinate of Toronto center will be obtained using Geocoder of well known Toronto location

5)The data frame will consist of three columns: PostalCode, Borough, and Neighborhood

6)Needs to process only those cells that have an assigned Borough. Ignore cells with a Borough that is Not assigned.

7)More than one neighborhood can exist in one postal code area. For example, in the table on the Wikipedia page, one can see that M5A is listed twice and has two neighborhoods: Harbourfront and Regent Park. These two rows will be combined into one row with the neighborhoods separated with a comma as shown in row 11 in the above table.

8)If a cell has a borough but a Not assigned neighborhood, then the neighborhood will be the same as the Borough. So for the 9th cell in the table on the Wikipedia page, the value of the Borough and the Neighborhood columns will be Queen's Park.
