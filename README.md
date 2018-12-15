# ggplotThemeTemplate
This is a brief document intended to share a ggplot theme template than can be modified as needed. Pull are requests welcome and appreciated!


`
master_plot_theme <- theme_light() +
  theme(
    # large plot title
    plot.title   = element_text(color  = "black",
                                face   = "bold",
                                size   = 15,
                                family = NULL,
                                hjust  = NULL,
                                vjust  = NULL),
    # x axis label
    axis.title.x = element_text(color  = "black",
                                face   = "bold",
                                size   = 12,
                                family = NULL,
                                hjust  = NULL,
                                vjust  = NULL),
    # y axis label
    axis.title.y = element_text(color  = "black",
                                face   = "bold",
                                size   = 12,
                                family = NULL,
                                angle  = NULL,
                                hjust  = NULL,
                                vjust  = NULL),
    # x axis tick labels
    axis.text.x  = element_text(face   = "bold",
                                color  = "black",
                                size   = 10,
                                family = NULL,
                                angle  = NULL,
                                hjust  = NULL,
                                vjust  = NULL),
    # y axis tick labels
    axis.text.y  = element_text(color  = "black",
                                face   = "bold",
                                size   = 10,
                                family = NULL,
                                angle  = NULL,
                                hjust  = NULL,
                                vjust  = NULL),
    # text for facet strips
    strip.text   = element_text(color  = "black",
                                face   = "bold",
                                size   = 15,
                                family = NULL,
                                hjust  = NULL,
                                vjust  = NULL),
    # background for facet strips
    strip.background = element_rect(color    = "black",
                                    fill     = "white",
                                    linetype = "solid"),
    # major and minor gridlines; can be added back w/ element_line(...)
    panel.grid.major.x = element_blank(),
    panel.grid.major.y = element_blank(),
    panel.grid.minor.x = element_blank(),
    panel.grid.minor.y = element_blank(),
    legend.position    = "none")
    `


