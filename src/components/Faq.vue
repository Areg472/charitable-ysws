<script setup lang="ts">
import {
    Accordion,
    AccordionContent,
    AccordionItem,
    AccordionTrigger,
} from "@/components/ui/accordion";
</script>

<template>
    <div class="w-52 lg:w-100">
        <Accordion
            type="single"
            collapsible
            class="w-full"
            default-value="item-1"
        >
            <AccordionItem value="item-1">
                <AccordionTrigger class="cursor-pointer"
                    >How will this YSWS work?</AccordionTrigger
                >
                <AccordionContent>
                    <p>
                        For every hour you ship a project, you will donate 5$ to
                        your favorite charity, project or non profit :D
                    </p>
                </AccordionContent>
            </AccordionItem>
            <AccordionItem value="item-2">
                <AccordionTrigger class="cursor-pointer"
                    >Will we be able to double dip with
                    flavortown?</AccordionTrigger
                >
                <AccordionContent>
                    <p>
                        We are having talks with the flavortown team about this,
                        since this is in early stage.
                    </p>
                </AccordionContent>
            </AccordionItem>
            <AccordionItem value="item-3">
                <AccordionTrigger class="cursor-pointer"
                    >Where can I get extra info about this?</AccordionTrigger
                >
                <AccordionContent>
                    <p>Join #charitable-ysws on slack to learn more!</p>
                </AccordionContent>
            </AccordionItem>
        </Accordion>
    </div>
</template>
