<template>
  <Html lang="en">
    <Head>
      <Title>AnZen | IT Security Notes</Title>
      <Meta name="viewport" :content="`width=device-width, initial-scale=1`" />
      <Meta
        name="description"
        :content="`IT Security Notes`"
      />
      <Meta
        name="keywords"
        content="AnZen, anzen, IT security, cybersecurity, threats, vulnerabilities, hacking"
      />
      <Link rel="icon" type="image/png" href="/samurai.png"></Link>
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="true">
      <link href="https://fonts.googleapis.com/css2?family=Rampart+One&display=swap&family=Leckerli+One&display=swap" rel="stylesheet">
      <link href="/reset.css" rel="stylesheet">
    </Head>
  </Html>
  <client-only>
    <Home />
  </client-only>
</template>
