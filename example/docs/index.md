# Quiz Example

## Single choice

<?quiz?>
question: Are you ready?
answer-correct: Yes!
answer: No!
answer: Maybe!
content:
<h2>Provide some additional content</h2>
<?/quiz?>

## Single choice - with HTML tag and empty content

<?quiz?>
question: 4. What is the syntax to use to declare the document character encoding as UTF-8?
answer: <?tag?><meta encoding="text/html; charset=utf-8"><?/tag?>
answer: <?tag?><meta charset="text/html; UTF-8"><?/tag?>
answer-correct: <?tag?><meta charset="utf-8"><?/tag?>
answer: <?tag?><meta lang="utf-8"><?/tag?>
content:
<?/quiz?>

## Multiple choice

<?quiz?>
question: Are you ready?
answer-correct: Yes!
answer: No!
answer-correct: Maybe!
content:
<h2>Provide some additional content</h2>
<?/quiz?>

## Disable for a page

See [disable.md](disable.md) for an example.
