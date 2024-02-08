VS Code'un otomatik tamamlama (autocomplete) özelliği, kod yazmayı hızlandıran ve daha verimli hale getiren bir özelliktir. Bu özellik, yazdığınız kodun bağlamına dayalı olarak öneriler sunar ve bu önerileri `Tab` tuşuna basarak kabul edebilirsiniz.

### Otomatik Tamamlama Nasıl Çalışır?

Otomatik tamamlama, yazdığınız kodun bağlamına dayalı olarak öneriler sunar. Örneğin, bir JavaScript fonksiyonu yazmaya başladığınızda, VS Code bu fonksiyonun muhtemel gövdesini önerir. Bu öneriyi kabul etmek için `Tab` tuşuna basabilirsiniz.

### Otomatik Tamamlama Ayarları

VS Code'da otomatik tamamlama özelliğini özelleştirebilirsiniz. İşte bazı ayarlar:

- `editor.tabCompletion`: Bu ayar, `Tab` tuşuna basıldığında en iyi eşleşen önerinin otomatik olarak eklenip eklenmeyeceğini kontrol eder. `on`, `off` veya `onlySnippets` değerlerini alabilir.

- `editor.quickSuggestions`: Bu ayar, yazarken otomatik olarak önerilerin gösterilip gösterilmeyeceğini kontrol eder. Yorumlar, dizeler ve diğer kod parçalarında yazarken bu kontrol edilebilir.

```json
{
	"editor.tabCompletion": "on",
	"editor.quickSuggestions": {
		"other": true,
		"comments": false,
		"strings": true
	}
}
```

### Otomatik Tamamlama İpuçları

- Otomatik tamamlama, kodunuzun bağlamına dayalı olarak çalışır. Bu nedenle, daha doğru öneriler almak için kodunuzu açık ve anlaşılır bir şekilde yazmaya çalışın.

- Otomatik tamamlama özelliği, belirli bir algoritmayı kullanmanızı veya bir sınıfa hangi yöntemlerin ve özelliklerin eklenmesi gerektiğini belirtmek için kod yorumlarını kullanabilirsiniz.

- Otomatik tamamlama özelliği, çok çeşitli diller ve çerçeveler için öneriler sunar ve özellikle Python, JavaScript, TypeScript, Ruby, Go, C# ve C++ için çok iyi çalışır.

### Sonuç

VS Code'un otomatik tamamlama özelliği, kod yazmayı hızlandıran ve daha verimli hale getiren güçlü bir araçtır. Ancak, her zaman kodunuzun kalitesini ve doğruluğunu kontrol etmek için kendi bilgi ve deneyiminizi kullanmanız önemlidir.

