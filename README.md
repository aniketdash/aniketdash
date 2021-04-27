```php
<?php

namespace Aniket Dash;

class About extends Me
{
    public function getWorkplace()
    {
        return [
            'University' => [
                'name' => 'University of Florida',
                'position' => 'Grad student'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Java::class,
            Javascript::class,
            Nodejs::class,
            Express::class,
            React::class,
            OCI::class,
            Aws::class,
        ];
    }
    
    public function currentProject(){
        return [Search performance uisng 
                Amazon Api Gateway,
                Lambda fuctions,
                Amazon S3,
                Amazon SQS,
                Amazon Cognito]
    }

    public function getFutureGoal()
    {
        return 'learn and contribute';
    }
}
```
[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=aniketdash)](https://github.com/anuraghazra/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=aniketdash&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
