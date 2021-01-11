# A Chinese folk recursive story

It is a good example to explain recursion.

```ruby
def tell_a_story
    puts 'In the past, there is a mountain.'
    puts 'In the mountain lies a temple.'
    puts 'At the temple live two monks.'
    puts 'An elder monk, and a child monk.'
    puts 'The elder monk is telling a story to the child one.'
    puts 'What he is telling is...'
    tell_a_story
end
```

In the past, there is a mountain.

In the mountain lies a temple.

At the temple live two monks.

An elder monk, and a child monk.

The elder monk is telling a story to the child one.

What he is telling is...

In the past, there is a mountain.

In the mountain lies a temple.

At the temple live two monks.

An elder monk, and a child monk.

The elder monk is telling a story to the child one.

What he is telling is...

In the past, there is a mountain.

.........