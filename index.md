{{range .Resources.Match ".images/*" }}
		<img src="{{ .RelPermalink }}"  /> 
{{ end }}