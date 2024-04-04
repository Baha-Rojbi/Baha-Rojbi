### Hi there 👋

It s time to break from tutorial hell and start working on real projects

```php
<?php
namespace BahaRojbi;

class About extends Me
{
    public function getCurrentPosition(): array
    {
        return [
            'education' => [
                'university' => 'The Private Higher School of Engineering and Technology',
                'grade' => 'First Year Masters Degree', 
                'degree' => 'Software Architecture Engineering'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Typescript::class,
            Java::class,
            Python::class,
            Csharp::class,
            Angular::class,
            SpringBoot::class,
            React::class,
            NodeJs::class,
            NextJs::class,
            .Net::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Land a first job.';
    }
}

