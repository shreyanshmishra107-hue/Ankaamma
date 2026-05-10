export default {
  async fetch(request) {

    const url = new URL(request.url);
    const id = url.searchParams.get("id");

    if (!id) {
      return new Response(
        JSON.stringify({
          error: "Missing id"
        }, null, 2),
        {
          status: 400,
          headers: {
            "content-type": "application/json",
            "access-control-allow-origin": "*"
          }
        }
      );
    }

    const api =
      `https://fx-sq4w.onrender.com/foot.php?id=${id}`;

    try {

      const res = await fetch(api, {
        method: "GET",
        headers: {
          "accept": "*/*",
          "origin": "https://sportseera1.pages.dev",
          "referer": "https://sportseera1.pages.dev/",
          "user-agent":
            "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/147.0.0.0 Safari/537.36"
        }
      });

      // Get response text
      const text = await res.text();

      // Return exact API response
      return new Response(text, {
        status: 200,
        headers: {
          "content-type": "application/json",
          "access-control-allow-origin": "*"
        }
      });

    } catch (e) {

      return new Response(
        JSON.stringify({
          success: false,
          error: e.toString()
        }, null, 2),
        {
          status: 500,
          headers: {
            "content-type": "application/json",
            "access-control-allow-origin": "*"
          }
        }
      );

    }
  }
}
