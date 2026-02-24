export default async function handler(req, res) {
  if (req.method !== "POST") return res.status(405).json({ reply: "Method not allowed" });
  const { text } = req.body || {};
  return res.status(200).json({ reply: `You said: ${text || ""}` });
}
