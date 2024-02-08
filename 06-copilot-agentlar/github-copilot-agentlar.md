
VS Code'da GitHub Copilot Chat özelliği, belirli bir konuda uzmanlaşmış "agent"lar aracılığıyla size yardımcı olur. Bu agentlar, belirli bir konuda yardımcı olabilecek uzmanlar olarak düşünülebilir. Şu anda aşağıdaki agentlar mevcuttur:

- `@workspace`: Çalışma alanınızdaki kod hakkında bilgiye sahip olan ve size ilgili dosyaları veya sınıfları bulmanızda yardımcı olabilen bir agenttir.

- `@vscode`: VS Code editöründeki komutlar ve özellikler hakkında bilgiye sahip olan ve size bunları kullanmanızda yardımcı olabilen bir agenttir.

- `@terminal`: Entegre terminal kabuğu ve içeriği hakkında bilgiye sahip olan bir agenttir.

Bu agentları, sohbet girişlerinize belirli bir agentı ekleyerek kullanabilirsiniz. Bu, Copilot'un size daha alakalı bir yanıt vermesine yardımcı olur. Örneğin, VS Code renklerini nasıl değiştireceğinizi öğrenmek istiyorsanız, `@vscode` agentına sorabilirsiniz.

Ayrıca, belirli türdeki sorular veya görevler için "slash komutları" da kullanabilirsiniz. Örneğin, `@workspace /explain` komutu, açık çalışma alanınızın bağlamında bir dosyayı veya kod seçimini açıklamak için kullanılabilir. Kullanılabilir agentlar ve slash komutları listesini görmek için `/` yazabilirsiniz.