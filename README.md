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

    public function getFutureGoal()
    {
        return 'learn and contribute';
    }
}
```
[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=aniketdash)](https://github.com/anuraghazra/github-readme-stats)
