# Control JSON serialization using attributes

Right now there are two attributes available for serializations

* `[JsonPropertyName]`. This controls the property name generated by the serialization. The name specified here will not be affected by `JsonSerializerOptions.PropertyNamingPolicy`.
* `[JsonIgnore]`. This tells the serializer not to generate the property in the output JSON doucument.