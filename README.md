# AdvancedProgramming

1. The Demo
    I load an R/Python package or call an API or present a Dashboard. With or without a UI, I can pull all available, machine readable financial data of a selected European bank for a selected period, thus making further analysis easier, because all of the data can be loaded from one single source. Additionally, I could calculate some metrics like RWA density, which require data from different sources.

2. The Shape
    in          a function with parameters that identify a time period and an identifier for a specific bank. Specifying an array of particular variables one wants to                  pull should also be available.

    out         the above mentioned data.
  
    on screen   A dataframe/table with dates as columns and financial statement rows or regulatory metrics as rows
  
  
3. The Size
   3.1 First Useful Version
      The ability to load a dataframe for an arbitrary European banking institution. One should also be able to see a mapping of figures to data sources upon request         (perhaps via a callable function), thus making their accounting treatment/economic meaning clear.
   
   3.2 Potentially this semester
     Some additional metrics that require calculation. 

   3.3 Not in this semester
     Further included analyses and visualization of data, at this point a standalone dashboard.

4. How we would know it works
   Seeing a complete table with no missing data or when data is actually missing, a clear indication of data missing in the source material, not in the pull.
   Being able to perform calculations with elements of the pulled object.
   
5. What could stop this
   If the publication structure of any of the underlying data sources changes, maintenance of bulk downloads/treating of source data is required.
   In the case of pulling data that originates from a non-banking regulator (for example the European Banking Authority's Basel III. Pillar 3 metrics), i.e. financial     statements, accounting treatments may vary across accounting standards, therefore a precise mapping of financial statements row to callable variable ID-s must be       met in order to see equivalent economic meanings when comparing data of several banks.
   
   
