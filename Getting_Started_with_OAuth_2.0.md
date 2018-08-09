我从 99 年开始一直在做 web api 开发，为公司内部网络应用构建基于 SOAP 协议的 web 服务, 同时帮助成千上万的程序员更好的使用 Google 的 基于 Rest 的 api (包括 Google Calendar, Picasa Web Albums, YouTube 等等)。这期间几乎每一个接口都需要用户授权才能正常使用。之前开发者们必须要用像 ClientLogin 和 AuthSub 这样的鉴权技术才能使用这些 google api。如果开发者想使用 Yahoo 的 api 他们也需要使用雅虎的 BBAuth 鉴权。 如果应用中需要使用多个公司的 api, 这对开发者来说就会是一种挑战。

Oauth1.0 为开发者减少了许多头疼的问题，使得他们在一个网站的众多接口中只需要使用一种鉴权技术就可以了。然而，　1.0 也会带来一些问题， 比如：密码签名 cryptographic signa- tures and limited definition of how to use it for authorizing applications not using a server-to-server web application flow ???. 我高兴的是 oauth2.0 几乎要完成了，他提供了简单易用的协议，使用于这些应用和其他多样的案例。

或许最让人激动人心的是，OpenID 链接标准（他基于 oauth2.0, 使用相同的 identity 来登陆多中应用 ??? ）的到来。 和我一起工作的许多开发者们也已经把早期版本的 openid 授权方式集成到了他们的应用中，整个过程非常轻松。openid 链接 就像 oauth2.0 一样，让开发者更容易集成授权功能。
