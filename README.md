Recommendation Engine
=====================================
A simple movie recommendation engine based on Apache Mahout.
<b>Inteface:</b>


```java
package com.jodisoft.recommendation.engine;

import java.util.List;
import org.apache.mahout.cf.taste.common.TasteException;
import com.jodisoft.recommendation.model.Movie;

public interface RecommendationEngine {
    public List<Movie> recommend(final Integer userId, final int howMany)
            throws TasteException;
}
```


<b>Data Model:</b>

![Settings Window](https://raw.githubusercontent.com/julesbond007/movie-recommendation-engine/master/docs/recommendation_tables.png)
