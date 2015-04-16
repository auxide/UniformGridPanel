# UniformGridPanel
Virtualized UniformGrid for use as a panel in WPF

Example Usage:
--------------
```
<ListBox ItemsSource="{Binding}">
    <ListBox.ItemsPanel>
        <ItemsPanelTemplate>
            <controls:UniformGridPanel Orientation="Horizontal"
                                       Columns="2" 
                                       Rows="2" />
        </ItemsPanelTemplate>
    </ListBox.ItemsPanel>
</ListBox>
```

Too easy!
