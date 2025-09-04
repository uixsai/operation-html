<!DOCTYPE html>
<!-- ⚠️ Mistake: <!doctype HTML> (wrong case) or missing ! -->
<!-- ✅ Correct: <!DOCTYPE html> -->

<html lang="en">
<!-- ⚠️ Mistake: <html> without lang -->
<!-- ✅ Correct: <html lang="en"> helps accessibility -->

<head>
    <meta charset="utf-8">
    <!-- ⚠️ Mistake: <meta charset=utf8> (missing quotes) -->
    <!-- ✅ Correct: <meta charset="utf-8"> -->

    <meta name="author" content="sk">
    <!-- ⚠️ Mistake: <meta author="sk"> -->
    <!-- ✅ Correct: must use name="author" -->

    <meta name="description"
        content="this is a page which gives you list of main  programming languages of being a webdev ">
    <!-- ⚠️ Mistake: forgetting quotes for content -->
    <!-- ✅ Correct: attributes must be quoted -->

    <meta name="keywords" content="html,css,Javascript,webdev">
    <!-- ⚠️ Mistake: <meta keywords="..."> -->
    <!-- ✅ Correct: must use name="keywords" -->

    <title>webdev languages</title>
    <!-- ⚠️ Mistake: forgetting </title> -->
    <!-- ✅ Correct: always close title -->

    <link rel="stylesheet" href="main.css" type="text/css">
    <!-- ⚠️ Mistake: <link= rel="stylesheet"> -->
    <!-- ✅ Correct: <link rel="stylesheet" href="..."> -->

    <link rel="icon" href="htmlsukuna.png" type="image/x-icon">
    <!-- ⚠️ Mistake: putting <link> inside <body> -->
    <!-- ✅ Correct: belongs inside <head> -->
</head>

<body>
    <!-- ⚠️ Mistake: multiple <body> tags or missing </body> -->
    <!-- ✅ Correct: only one body -->

    <hr>
    <!-- ⚠️ Mistake: writing </hr> -->
    <!-- ✅ Correct: <hr> is self-closing -->

    <h1>DOWN BELOW ARE ALL <em>webdev</em> languages </h1>
    <!-- ⚠️ Mistake: wrong nesting like <h1><em>..</h1></em> -->
    <!-- ✅ Correct: close inner tag first -->

    <p><strong>1.html</strong></p>
    <!-- ⚠️ Mistake: <p>1.html<p> (forgetting /p) -->
    <!-- ✅ Correct: <p>...</p> -->

    <p>2.css</p>
    <p>3.javascript</p>

    <hr>
    <hr>

    <h2><em>NOW THE CURRENT FILE YOUR VIEWING IS HTML . </em></h2>
    <!-- ⚠️ Mistake: <h2><em>...<h2></em> (wrong order) -->
    <!-- ✅ Correct: last opened must close first -->

    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;......this HTML file is
        brought you by :) <strong><em>v.s code </em></strong>
    </p>
    <!-- ⚠️ Mistake: too many &nbsp; for spacing -->
    <!-- ✅ Better: use CSS margin or padding -->

    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;......<em><strong>
        <abbr title="VISUAL STUDIO">V.S</abbr>
    </strong></em>[hover over this]
    <!-- ⚠️ Mistake: <abbr=VISUAL STUDIO> -->
    <!-- ✅ Correct: <abbr title="..."> -->

    <p>thats it ~
        now your
        ready to go
        start
        these topic
        learning in
        order on
        youtube
    </p>
    <!-- ⚠️ Mistake: <p> with block elements inside -->
    <!-- ✅ Correct: only inline tags allowed in <p> -->

    <hr>
    <hr>

    &lt;&lt;&lt;&lt;&lt;&copy;<strong><em>
            SK - DAY1
        </em></strong>
    &gt;&gt;&gt;&gt;&gt;
    <!-- ⚠️ Mistake: writing < instead of &lt; -->
    <!-- ✅ Correct: use entities (&lt; &gt; &copy;) -->

    <hr>
</body>

</html>
<!-- ⚠️ Mistake: forgetting </html> -->
<!-- ✅ Correct: must close html -->
