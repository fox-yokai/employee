# employee-directory
Quick view of the employee directory
## How to Use
Open the page and the list of employee will automatially be displayed
## Code Highlights
```
{directory.results.map(result => (
                <div className="row" key={result.id.value}>
                    <div className="col-sm thumbnail">
                        <img src={result.picture.thumbnail} alt={result.name.first}></img>
                    </div>
                    <div className="col-sm name">
                        {result.name.first} {result.name.last}
                    </div>
                    <div className="col-sm phone">
                        {result.phone}
                    </div>
                    <div className="col-sm email">
                        {result.email}
                    </div>
                    <div className="col-sm dob">
                        {result.dob.date.substring(0, 10)}
```